{
  "info": {
    "name": "StatusPage.io Get a list of metrics created for a linked metrics provider",
    "_postman_id": "1f9411fb-e85c-4b8e-9469-3099f2b50322",
    "description": "Get a list of metrics created for a linked metrics provider",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Pages",
      "item": [
        {
          "id": "8109e261-6ce0-494d-ac34-c2b213879f5d",
          "name": "get-your-page-profile",
          "request": {
            "url": "http://example.com/api/pages/[page_id].json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get your page profile"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "42831a35-ef3b-4f9e-bf1f-b87596d2d1c8"
            }
          ]
        },
        {
          "id": "358dfdcf-fc02-4538-96f2-c22f83ef6840",
          "name": "update-your-page-profile",
          "request": {
            "url": "http://example.com/api/pages/[page_id].json?basic layout only, 170x45 or 340x90 is best=basic%20layout%20only%2C%20170x45%20or%20340x90%20is%20best&page[allow_email_subscribers]=page%5Ballow_email_subscribers%5D&page[allow_incident_subscribers]=page%5Ballow_incident_subscribers%5D&page[allow_page_subscribers]=page%5Ballow_page_subscribers%5D&page[allow_sms_subscribers]=page%5Ballow_sms_subscribers%5D&page[city]=page%5Bcity%5D&page[country]=page%5Bcountry%5D&page[css_body_background_color]=page%5Bcss_body_background_color%5D&page[css_font_color]=page%5Bcss_font_color%5D&page[css_greens]=page%5Bcss_greens%5D&page[css_light_font_color]=page%5Bcss_light_font_color%5D&page[css_oranges]=page%5Bcss_oranges%5D&page[css_reds]=page%5Bcss_reds%5D&page[css_yellows]=page%5Bcss_yellows%5D&page[domain]=page%5Bdomain%5D&page[hero_cover_url]=page%5Bhero_cover_url%5D&page[layout]=page%5Blayout%5D&page[name]=page%5Bname%5D&page[notifications_from_email]=page%5Bnotifications_from_email%5D&page[state]=page%5Bstate%5D&page[subdomain]=page%5Bsubdomain%5D&page[time_zone]=page%5Btime_zone%5D&page[transactional_logo_url]=page%5Btransactional_logo_url%5D&page[url]=page%5Burl%5D&premium layout only, 850x315 or 1700x630 is best=premium%20layout%20only%2C%20850x315%20or%201700x630%20is%20best",
            "method": "PATCH",
            "body": {
              "mode": "raw"
            },
            "description": "Update your page profile"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2e29bf93-b0b1-46a8-9029-27815c4137c6"
            }
          ]
        }
      ]
    },
    {
      "name": "Components",
      "item": [
        {
          "id": "c5162866-f3b9-4e9a-8148-7c1341b8ca7b",
          "name": "get-a-list-of-all-components",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/components.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of all components"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bcb573d1-6898-45b4-b35b-1f3cfd7123e5"
            }
          ]
        },
        {
          "id": "8d1f852a-df43-4d29-afd1-34776572782e",
          "name": "create-a-component",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/components.json?component[description]=component%5Bdescription%5D&component[group_id]=component%5Bgroup_id%5D&component[name]=component%5Bname%5D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a component"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8837ae94-9b50-454a-a164-eac4a4efb4bc"
            }
          ]
        },
        {
          "id": "38345dc6-c1a7-4165-a896-6a044db3050a",
          "name": "delete-a-component",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/components/[component_id].json",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete a component"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0c50090f-0cef-4e0c-a2d2-8bcd7250e5b8"
            }
          ]
        }
      ]
    },
    {
      "name": "Page Access Group",
      "item": [
        {
          "id": "fa7f0034-b650-48fe-9930-389948070869",
          "name": "update-a-component",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/components/[component_id].json?component[description]=component%5Bdescription%5D&component[name]=component%5Bname%5D&component[status]=component%5Bstatus%5D",
            "method": "PATCH",
            "body": {
              "mode": "raw"
            },
            "description": "Update a component"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a6b25421-bce3-4256-992b-6daa73838388"
            }
          ]
        }
      ]
    },
    {
      "name": "Incidents",
      "item": [
        {
          "id": "766042bf-c9bc-4a02-bec3-61c0600f61d8",
          "name": "get-a-list-of-all-incidents",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/incidents.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of all incidents"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8fc48503-2af3-44f6-bf52-3896964f8b05"
            }
          ]
        },
        {
          "id": "ac986a47-cf84-4f88-9f3a-cd044bb96c96",
          "name": "create-a-realtime-incident",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/incidents.json?incident[backfilled]=incident%5Bbackfilled%5D&incident[backfill_date]=incident%5Bbackfill_date%5D&incident[component_ids]=incident%5Bcomponent_ids%5D&incident[impact_override]=incident%5Bimpact_override%5D&incident[message]=incident%5Bmessage%5D&incident[name]=incident%5Bname%5D&incident[scheduled_auto_completed]=incident%5Bscheduled_auto_completed%5D&incident[scheduled_auto_in_progress]=incident%5Bscheduled_auto_in_progress%5D&incident[scheduled_for]=incident%5Bscheduled_for%5D&incident[scheduled_remind_prior]=incident%5Bscheduled_remind_prior%5D&incident[scheduled_until]=incident%5Bscheduled_until%5D&incident[status]=incident%5Bstatus%5D&incident[wants_twitter_update]=incident%5Bwants_twitter_update%5D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a realtime incident"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bc3269ed-0289-49bc-a525-21f00a4b6935"
            }
          ]
        },
        {
          "id": "661f8671-5fc2-46a7-b70e-a9c44142d537",
          "name": "unresolved-only",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/incidents/unresolved.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unresolved Only"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "83b47993-2f4c-4a61-b8b0-39db344017e2"
            }
          ]
        },
        {
          "id": "04bfed28-a2c8-4e4f-8f3e-c4154e7bc388",
          "name": "scheduled-only",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/incidents/scheduled.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Scheduled Only"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ec548568-efd8-4119-aeb0-dd3e784178d4"
            }
          ]
        },
        {
          "id": "751fb664-e173-4326-9096-c587c71f0da2",
          "name": "delete-an-incident",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/incidents/[incident_id].json",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete an incident"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a1eb49f8-c91f-43df-9a13-34b1143327d6"
            }
          ]
        },
        {
          "id": "d1fcdb4b-efbe-492b-9a3c-0a3bf3bf02de",
          "name": "update-an-incident-only-applies-to-realtime-and-scheduled-incidents",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/incidents/[incident_id].json?at the same time to avoid two separate incident updates being generated.=at%20the%20same%20time%20to%20avoid%20two%20separate%20incident%20updates%20being%20generated.&ENDPOINT=ENDPOINT&incident[component_ids]=incident%5Bcomponent_ids%5D&incident[impact_override]=incident%5Bimpact_override%5D&incident[message]=incident%5Bmessage%5D&incident[name]=incident%5Bname%5D&incident[status]=incident%5Bstatus%5D&incident[wants_twitter_update]=incident%5Bwants_twitter_update%5D&MUTABLE=MUTABLE&PATCH /pages/[page_id]/incidents/[incident_id].json=PATCH%20%2Fpages%2F%5Bpage_id%5D%2Fincidents%2F%5Bincident_id%5D.json",
            "method": "PATCH",
            "body": {
              "mode": "raw"
            },
            "description": "Update an incident (only applies to realtime and scheduled incidents)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f8bbf20f-c7df-4014-bf5a-91afd6d12d29"
            }
          ]
        },
        {
          "id": "0abe7aa4-c8bc-4df5-9513-f0c9102c44e8",
          "name": "tune-an-incident-update",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/incidents/[incident_id]/incident_updates/[incident_update_id].json?incident_update[body]=incident_update%5Bbody%5D&incident_update[display_at]=incident_update%5Bdisplay_at%5D",
            "method": "PATCH",
            "body": {
              "mode": "raw"
            },
            "description": "Tune an Incident Update"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "753d3567-68ae-4861-8f20-cacad8979ff6"
            }
          ]
        }
      ]
    },
    {
      "name": "Subscribers",
      "item": [
        {
          "id": "e117b17b-48f2-408d-82a7-dc18ef3456b8",
          "name": "delete-a-subscriber",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/subscribers/[subscriber_id].json",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete a subscriber"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e126fe6-4400-4f98-920f-2183a5bc0ec2"
            }
          ]
        }
      ]
    },
    {
      "name": "Metrics",
      "item": [
        {
          "id": "29f6ae62-7983-43b0-ac38-71ea416d4eb7",
          "name": "get-a-list-of-available-public-metric-providers",
          "request": {
            "url": "http://example.com/api/metrics_providers.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of available public metric providers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e4f5260-5a0c-4376-995f-1f60abc33f86"
            }
          ]
        }
      ]
    },
    {
      "name": "Metric Providers",
      "item": [
        {
          "id": "1953d03f-8093-4db6-9685-ac5797f860e7",
          "name": "get-a-list-of-metric-providers-linked-to-your-page",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/metrics_providers.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of metric providers linked to your page"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "799f2147-2d4e-41bf-b69b-769ce2dc915b"
            }
          ]
        },
        {
          "id": "6a810c39-6379-4075-a5aa-a5cf1aae6cdc",
          "name": "get-a-list-of-metrics-created-for-a-linked-metrics-provider",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/metrics_providers/[metrics_provider_id]/metrics.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of metrics created for a linked metrics provider"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "80574a61-e10c-4ffe-927b-f3dfc9e969a7"
            }
          ]
        }
      ]
    }
  ]
}