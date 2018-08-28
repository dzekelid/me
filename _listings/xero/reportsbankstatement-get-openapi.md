---
swagger: "2.0"
x-collection-name: Xero
x-complete: 0
info:
  title: Clarity Accounting Get Reports Bankstatement
  description: Get reports bankstatement.
  contact:
    name: Xero Developer Team
    url: https://developer.xero.com
  version: "2.0"
host: api.xero.com
basePath: /api.xro/2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Accounts/{AccountID}/Attachments:
    get:
      summary: Get Accounts Attachments
      description: Get accounts account attachments.
      operationId: getAccountsAccountAttachments
      x-api-path-slug: accountsaccountidattachments-get
      parameters:
      - in: path
        name: AccountID
        description: The Xero generated unique identifier for an account
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - AccountID
      - Attachments
  /Accounts/{AccountID}/Attachments/{FileName}:
    get:
      summary: Get Accounts Attachments Filename
      description: Get accounts account attachments filename.
      operationId: getAccountsAccountAttachmentsFilename
      x-api-path-slug: accountsaccountidattachmentsfilename-get
      parameters:
      - in: path
        name: AccountID
        description: The Xero generated unique identifier for an account
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - AccountID
      - Attachments
      - FileName
    post:
      summary: Post Accounts Attachments Filename
      description: Post accounts account attachments filename.
      operationId: postAccountsAccountAttachmentsFilename
      x-api-path-slug: accountsaccountidattachmentsfilename-post
      parameters:
      - in: path
        name: AccountID
        description: The Xero generated unique identifier for an account
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - AccountID
      - Attachments
      - FileName
  /BankTransactions/{BankTransactionID}/Attachments:
    get:
      summary: Get Bank Transactions Banktransaction Attachments
      description: Get banktransactions banktransaction attachments.
      operationId: getBanktransactionsBanktransactionAttachments
      x-api-path-slug: banktransactionsbanktransactionidattachments-get
      parameters:
      - in: path
        name: BankTransactionID
        description: The Xero generated unique identifier for an bank transaction
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
      - BankTransactionID
      - Attachments
  /BankTransactions/{BankTransactionID}/Attachments/{FileName}:
    get:
      summary: Get Bank Transactions Banktransaction Attachments Filename
      description: Get banktransactions banktransaction attachments filename.
      operationId: getBanktransactionsBanktransactionAttachmentsFilename
      x-api-path-slug: banktransactionsbanktransactionidattachmentsfilename-get
      parameters:
      - in: path
        name: BankTransactionID
        description: The Xero generated unique identifier for an bank transaction
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
      - BankTransactionID
      - Attachments
      - FileName
    post:
      summary: Post Bank Transactions Banktransaction Attachments Filename
      description: Post banktransactions banktransaction attachments filename.
      operationId: postBanktransactionsBanktransactionAttachmentsFilename
      x-api-path-slug: banktransactionsbanktransactionidattachmentsfilename-post
      parameters:
      - in: path
        name: BankTransactionID
        description: The Xero generated unique identifier for an bank transaction
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
      - BankTransactionID
      - Attachments
      - FileName
  /BankTransfers/{BankTransferID}/Attachments/{FileName}:
    get:
      summary: Get Banks Transfers Attachments Filename
      description: Get banktransfers banktransfer attachments filename.
      operationId: getBanktransfersBanktransferAttachmentsFilename
      x-api-path-slug: banktransfersbanktransferidattachmentsfilename-get
      parameters:
      - in: path
        name: BankTransferID
        description: The Xero generated unique identifier for an BankTransfer
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransfers
      - BankTransferID
      - Attachments
      - FileName
    post:
      summary: Post Banks Transfers Attachments Filename
      description: Post banktransfers banktransfer attachments filename.
      operationId: postBanktransfersBanktransferAttachmentsFilename
      x-api-path-slug: banktransfersbanktransferidattachmentsfilename-post
      parameters:
      - in: path
        name: BankTransferID
        description: The Xero generated unique identifier for a BankTransfer
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      responses:
        200:
          description: OK
      tags:
      - BankTransfers
      - BankTransferID
      - Attachments
      - FileName
  /BrandingThemes:
    get:
      summary: Get Brandingthemes
      description: Get brandingthemes.
      operationId: getBrandingthemes
      x-api-path-slug: brandingthemes-get
      responses:
        200:
          description: OK
      tags:
      - BrandingThemes
    x-related-model:
      summary: X-related-model Brandingthemes
      description: X-related-model brandingthemes.
      operationId: x-related-modelBrandingthemes
      x-api-path-slug: brandingthemes-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - BrandingThemes
  /BrandingThemes/{BrandingThemeID}:
    get:
      summary: Get Brandingthemes Brandingtheme
      description: Get brandingthemes brandingtheme.
      operationId: getBrandingthemesBrandingtheme
      x-api-path-slug: brandingthemesbrandingthemeid-get
      parameters:
      - in: path
        name: BrandingThemeID
      responses:
        200:
          description: OK
      tags:
      - BrandingThemes
      - BrandingThemeID
    x-related-model:
      summary: X-related-model Brandingthemes Brandingtheme
      description: X-related-model brandingthemes brandingtheme.
      operationId: x-related-modelBrandingthemesBrandingtheme
      x-api-path-slug: brandingthemesbrandingthemeid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - BrandingThemes
      - BrandingThemeID
  /Contacts/{ContactID}/Attachments:
    get:
      summary: Get Contacts Contact Attachments
      description: Get contacts contact attachments.
      operationId: getContactsContactAttachments
      x-api-path-slug: contactscontactidattachments-get
      parameters:
      - in: path
        name: ContactID
        description: The Xero generated unique identifier for a Contact
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - ContactID
      - Attachments
  /Contacts/{ContactID}/Attachments/{FileName}:
    get:
      summary: Get Contacts Contact Attachments Filename
      description: Get contacts contact attachments filename.
      operationId: getContactsContactAttachmentsFilename
      x-api-path-slug: contactscontactidattachmentsfilename-get
      parameters:
      - in: path
        name: ContactID
        description: The Xero generated unique identifier for a Contact
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - ContactID
      - Attachments
      - FileName
    post:
      summary: Post Contacts Contact Attachments Filename
      description: Post contacts contact attachments filename.
      operationId: postContactsContactAttachmentsFilename
      x-api-path-slug: contactscontactidattachmentsfilename-post
      parameters:
      - in: path
        name: ContactID
        description: The Xero generated unique identifier for a Contact
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - ContactID
      - Attachments
      - FileName
  /CreditNotes/{CreditNoteID}/Attachments:
    get:
      summary: Get Creditnotes Creditnote Attachments
      description: Get creditnotes creditnote attachments.
      operationId: getCreditnotesCreditnoteAttachments
      x-api-path-slug: creditnotescreditnoteidattachments-get
      parameters:
      - in: path
        name: CreditNoteID
        description: The Xero generated unique identifier for a CreditNote
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
      - Attachments
  /CreditNotes/{CreditNoteID}/Attachments/{FileName}:
    get:
      summary: Get Creditnotes Creditnote Attachments Filename
      description: Get creditnotes creditnote attachments filename.
      operationId: getCreditnotesCreditnoteAttachmentsFilename
      x-api-path-slug: creditnotescreditnoteidattachmentsfilename-get
      parameters:
      - in: path
        name: CreditNoteID
        description: The Xero generated unique identifier for a CreditNote
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
      - Attachments
      - FileName
    post:
      summary: Post Creditnotes Creditnote Attachments Filename
      description: Post creditnotes creditnote attachments filename.
      operationId: postCreditnotesCreditnoteAttachmentsFilename
      x-api-path-slug: creditnotescreditnoteidattachmentsfilename-post
      parameters:
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: CreditNoteID
        description: The Xero generated unique identifier for a CreditNote
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
      - Attachments
      - FileName
  /Invoices/{InvoiceID}/Attachments:
    get:
      summary: Get Invoices Invoice Attachments
      description: Get invoices invoice attachments.
      operationId: getInvoicesInvoiceAttachments
      x-api-path-slug: invoicesinvoiceidattachments-get
      parameters:
      - in: path
        name: InvoiceID
        description: The Xero generated unique identifier for an Invoice
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Invoices
      - InvoiceID
      - Attachments
  /Invoices/{InvoiceID}/Attachments/{FileName}:
    get:
      summary: Get Invoices Invoice Attachments Filename
      description: Get invoices invoice attachments filename.
      operationId: getInvoicesInvoiceAttachmentsFilename
      x-api-path-slug: invoicesinvoiceidattachmentsfilename-get
      parameters:
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: path
        name: InvoiceID
        description: The Xero generated unique identifier for an Invoice
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Invoices
      - InvoiceID
      - Attachments
      - FileName
    post:
      summary: Post Invoices Invoice Attachments Filename
      description: Post invoices invoice attachments filename.
      operationId: postInvoicesInvoiceAttachmentsFilename
      x-api-path-slug: invoicesinvoiceidattachmentsfilename-post
      parameters:
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      - in: path
        name: InvoiceID
        description: The Xero generated unique identifier for an Invoice
      responses:
        200:
          description: OK
      tags:
      - Invoices
      - InvoiceID
      - Attachments
      - FileName
  /ManualJournals/{ManualJournalID}/Attachments:
    get:
      summary: Get Manualjournals Manualjournal Attachments
      description: Get manualjournals manualjournal attachments.
      operationId: getManualjournalsManualjournalAttachments
      x-api-path-slug: manualjournalsmanualjournalidattachments-get
      parameters:
      - in: path
        name: ManualJournalID
        description: The Xero generated unique identifier for a Manual Journal
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ManualJournals
      - ManualJournalID
      - Attachments
  /ManualJournals/{ManualJournalID}/Attachments/{FileName}:
    get:
      summary: Get Manualjournals Manualjournal Attachments Filename
      description: Get manualjournals manualjournal attachments filename.
      operationId: getManualjournalsManualjournalAttachmentsFilename
      x-api-path-slug: manualjournalsmanualjournalidattachmentsfilename-get
      parameters:
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: path
        name: ManualJournalID
        description: The Xero generated unique identifier for a Manual Journal
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ManualJournals
      - ManualJournalID
      - Attachments
      - FileName
    post:
      summary: Post Manualjournals Manualjournal Attachments Filename
      description: Post manualjournals manualjournal attachments filename.
      operationId: postManualjournalsManualjournalAttachmentsFilename
      x-api-path-slug: manualjournalsmanualjournalidattachmentsfilename-post
      parameters:
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      - in: path
        name: ManualJournalID
        description: The Xero generated unique identifier for a Manual Journal
      responses:
        200:
          description: OK
      tags:
      - ManualJournals
      - ManualJournalID
      - Attachments
      - FileName
  /Overpayments:
    get:
      summary: Get Overpayments
      description: Get overpayments.
      operationId: getOverpayments
      x-api-path-slug: overpayments-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Overpayments
    x-related-model:
      summary: X-related-model Overpayments
      description: X-related-model overpayments.
      operationId: x-related-modelOverpayments
      x-api-path-slug: overpayments-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Overpayments
  /Overpayments/{OverpaymentID}:
    get:
      summary: Get Overpayments Overpayment
      description: Get overpayments overpayment.
      operationId: getOverpaymentsOverpayment
      x-api-path-slug: overpaymentsoverpaymentid-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: OverpaymentID
      responses:
        200:
          description: OK
      tags:
      - Overpayments
      - OverpaymentID
    x-related-model:
      summary: X-related-model Overpayments Overpayment
      description: X-related-model overpayments overpayment.
      operationId: x-related-modelOverpaymentsOverpayment
      x-api-path-slug: overpaymentsoverpaymentid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Overpayments
      - OverpaymentID
  /Overpayments/{OverpaymentID}/Allocations:
    put:
      summary: Put Overpayments Overpayment Allocations
      description: Put overpayments overpayment allocations.
      operationId: putOverpaymentsOverpaymentAllocations
      x-api-path-slug: overpaymentsoverpaymentidallocations-put
      parameters:
      - in: body
        name: Allocations
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: OverpaymentID
      responses:
        200:
          description: OK
      tags:
      - Overpayments
      - OverpaymentID
      - Ocations
    x-related-model:
      summary: X-related-model Overpayments Overpayment Allocations
      description: X-related-model overpayments overpayment allocations.
      operationId: x-related-modelOverpaymentsOverpaymentAllocations
      x-api-path-slug: overpaymentsoverpaymentidallocations-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Overpayments
      - OverpaymentID
      - Ocations
  /Payments:
    get:
      summary: Get Payments
      description: Get payments.
      operationId: getPayments
      x-api-path-slug: payments-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Payments
    post:
      summary: Post Payments
      description: Post payments.
      operationId: postPayments
      x-api-path-slug: payments-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: Payments
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Payments
    put:
      summary: Put Payments
      description: Put payments.
      operationId: putPayments
      x-api-path-slug: payments-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: Payments
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Payments
    x-related-model:
      summary: X-related-model Payments
      description: X-related-model payments.
      operationId: x-related-modelPayments
      x-api-path-slug: payments-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Payments
  /Payments/{PaymentID}:
    get:
      summary: Get Payments Payment
      description: Get payments payment.
      operationId: getPaymentsPayment
      x-api-path-slug: paymentspaymentid-get
      parameters:
      - in: path
        name: PaymentID
      responses:
        200:
          description: OK
      tags:
      - Payments
      - PaymentID
    post:
      summary: Post Payments Payment
      description: Post payments payment.
      operationId: postPaymentsPayment
      x-api-path-slug: paymentspaymentid-post
      parameters:
      - in: path
        name: PaymentID
      - in: body
        name: Payments
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Payments
      - PaymentID
    x-related-model:
      summary: X-related-model Payments Payment
      description: X-related-model payments payment.
      operationId: x-related-modelPaymentsPayment
      x-api-path-slug: paymentspaymentid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Payments
      - PaymentID
  /Prepayments:
    get:
      summary: Get Prepayments
      description: Get prepayments.
      operationId: getPrepayments
      x-api-path-slug: prepayments-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Prepayments
    x-related-model:
      summary: X-related-model Prepayments
      description: X-related-model prepayments.
      operationId: x-related-modelPrepayments
      x-api-path-slug: prepayments-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Prepayments
  /Prepayments/{PrepaymentID}:
    get:
      summary: Get Prepayments Prepayment
      description: Get prepayments prepayment.
      operationId: getPrepaymentsPrepayment
      x-api-path-slug: prepaymentsprepaymentid-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: PrepaymentID
      responses:
        200:
          description: OK
      tags:
      - Prepayments
      - PrepaymentID
    x-related-model:
      summary: X-related-model Prepayments Prepayment
      description: X-related-model prepayments prepayment.
      operationId: x-related-modelPrepaymentsPrepayment
      x-api-path-slug: prepaymentsprepaymentid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Prepayments
      - PrepaymentID
  /Prepayments/{PrepaymentID}/Allocations:
    put:
      summary: Put Prepayments Prepayment Allocations
      description: Put prepayments prepayment allocations.
      operationId: putPrepaymentsPrepaymentAllocations
      x-api-path-slug: prepaymentsprepaymentidallocations-put
      parameters:
      - in: body
        name: Allocations
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: PrepaymentID
      responses:
        200:
          description: OK
      tags:
      - Prepayments
      - PrepaymentID
      - Ocations
    x-related-model:
      summary: X-related-model Prepayments Prepayment Allocations
      description: X-related-model prepayments prepayment allocations.
      operationId: x-related-modelPrepaymentsPrepaymentAllocations
      x-api-path-slug: prepaymentsprepaymentidallocations-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Prepayments
      - PrepaymentID
      - Ocations
  /PurchaseOrders/{PurchaseOrderID}/Attachments:
    get:
      summary: Get Purchaseorders Purchaseorder Attachments
      description: Get purchaseorders purchaseorder attachments.
      operationId: getPurchaseordersPurchaseorderAttachments
      x-api-path-slug: purchaseorderspurchaseorderidattachments-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: PurchaseOrderID
        description: The Xero generated unique identifier for a purchase order
      responses:
        200:
          description: OK
      tags:
      - PurchaseOrders
      - PurchaseOrderID
      - Attachments
  /PurchaseOrders/{PurchaseOrderID}/Attachments/{FileName}:
    get:
      summary: Get Purchaseorders Purchaseorder Attachments Filename
      description: Get purchaseorders purchaseorder attachments filename.
      operationId: getPurchaseordersPurchaseorderAttachmentsFilename
      x-api-path-slug: purchaseorderspurchaseorderidattachmentsfilename-get
      parameters:
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: query
        name: No Name
      - in: path
        name: PurchaseOrderID
        description: The Xero generated unique identifier for a purchase order
      responses:
        200:
          description: OK
      tags:
      - PurchaseOrders
      - PurchaseOrderID
      - Attachments
      - FileName
    post:
      summary: Post Purchaseorders Purchaseorder Attachments Filename
      description: Post purchaseorders purchaseorder attachments filename.
      operationId: postPurchaseordersPurchaseorderAttachmentsFilename
      x-api-path-slug: purchaseorderspurchaseorderidattachmentsfilename-post
      parameters:
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      - in: path
        name: PurchaseOrderID
        description: The Xero generated unique identifier for a purchase order
      responses:
        200:
          description: OK
      tags:
      - PurchaseOrders
      - PurchaseOrderID
      - Attachments
      - FileName
  /Receipts/{ReceiptID}/Attachments:
    get:
      summary: Get Receipts Receipt Attachments
      description: Get receipts receipt attachments.
      operationId: getReceiptsReceiptAttachments
      x-api-path-slug: receiptsreceiptidattachments-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: ReceiptID
        description: The Xero generated unique identifier for a Receipt
      responses:
        200:
          description: OK
      tags:
      - Receipts
      - ReceiptID
      - Attachments
  /Receipts/{ReceiptID}/Attachments/{FileName}:
    get:
      summary: Get Receipts Receipt Attachments Filename
      description: Get receipts receipt attachments filename.
      operationId: getReceiptsReceiptAttachmentsFilename
      x-api-path-slug: receiptsreceiptidattachmentsfilename-get
      parameters:
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: query
        name: No Name
      - in: path
        name: ReceiptID
        description: The Xero generated unique identifier for a Receipt
      responses:
        200:
          description: OK
      tags:
      - Receipts
      - ReceiptID
      - Attachments
      - FileName
    post:
      summary: Post Receipts Receipt Attachments Filename
      description: Post receipts receipt attachments filename.
      operationId: postReceiptsReceiptAttachmentsFilename
      x-api-path-slug: receiptsreceiptidattachmentsfilename-post
      parameters:
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      - in: path
        name: ReceiptID
        description: The Xero generated unique identifier for a Receipt
      responses:
        200:
          description: OK
      tags:
      - Receipts
      - ReceiptID
      - Attachments
      - FileName
  /RepeatingInvoices/{RepeatingInvoiceID}/Attachments:
    get:
      summary: Get Repeatinginvoices Repeatinginvoice Attachments
      description: Get repeatinginvoices repeatinginvoice attachments.
      operationId: getRepeatinginvoicesRepeatinginvoiceAttachments
      x-api-path-slug: repeatinginvoicesrepeatinginvoiceidattachments-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: RepeatingInvoiceID
        description: The Xero generated unique identifier for a RepeatingInvoice
      responses:
        200:
          description: OK
      tags:
      - RepeatingInvoices
      - RepeatingInvoiceID
      - Attachments
  /RepeatingInvoices/{RepeatingInvoiceID}/Attachments/{FileName}:
    get:
      summary: Get Repeatinginvoices Repeatinginvoice Attachments Filename
      description: Get repeatinginvoices repeatinginvoice attachments filename.
      operationId: getRepeatinginvoicesRepeatinginvoiceAttachmentsFilename
      x-api-path-slug: repeatinginvoicesrepeatinginvoiceidattachmentsfilename-get
      parameters:
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: query
        name: No Name
      - in: path
        name: RepeatingInvoiceID
        description: The Xero generated unique identifier for a RepeatingInvoice
      responses:
        200:
          description: OK
      tags:
      - RepeatingInvoices
      - RepeatingInvoiceID
      - Attachments
      - FileName
  /Reports/BankStatement:
    get:
      summary: Get Reports Bankstatement
      description: Get reports bankstatement.
      operationId: getReportsBankstatement
      x-api-path-slug: reportsbankstatement-get
      parameters:
      - in: query
        name: bankAccountID
        description: bankAccountID e
      - in: query
        name: fromDate
        description: YYYY-MM-DD
      - in: query
        name: toDate
        description: YYYY-MM-DD
      responses:
        200:
          description: OK
      tags:
      - Reports
      - BankStatement
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---