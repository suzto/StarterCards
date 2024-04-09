### Card payload

````
{
  "type": "AdaptiveCard",
  "$schema": "http://adaptivecards.io/schemas/adaptive-card.json",
  "version": "1.5",
  "body": [
    {
      "type": "Image",
      "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_three/assets/video_image.png",
      "altText": "Web Development Bootcamp Video"
    },
    {
      "type": "TextBlock",
      "text": "Web Development Bootcamp",
      "wrap": true,
      "size": "Large",
      "weight": "Bolder"
    },
    {
      "type": "TextBlock",
      "text": "HackLab Films",
      "wrap": true,
      "spacing": "None",
      "weight": "Bolder"
    },
    {
      "type": "TextBlock",
      "text": "24m · 17.1M views · 2 months ago",
      "wrap": true,
      "spacing": "None"
    },
    {
      "type": "ActionSet",
      "targetWidth": "atLeast:narrow",
      "actions": [
        {
          "type": "Action.OpenUrl",
          "title": "Open",
          "url": "https://adaptivecards.io/"
        },
        {
          "type": "Action.OpenUrl",
          "title": "Add to calendar",
          "url": "https://adaptivecards.io/",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_three/assets/add_to_calendar_icon.png"
        },
        {
          "type": "Action.OpenUrl",
          "title": "Share in Teams",
          "mode": "secondary",
          "url": "https://adaptivecards.io/",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_three/assets/add_to_calendar_icon.png"
        },
        {
          "type": "Action.OpenUrl",
          "title": "Download",
          "url": "https://adaptivecards.io/",
          "mode": "secondary",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_three/assets/add_to_calendar_icon.png"
        },
        {
          "type": "Action.OpenUrl",
          "title": "Copy link",
          "mode": "secondary",
          "url": "https://adaptivecards.io/",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_three/assets/add_to_calendar_icon.png"
        }
      ]
    },
    {
      "type": "ActionSet",
      "targetWidth": "veryNarrow",
      "actions": [
        {
          "type": "Action.OpenUrl",
          "title": "Open",
          "url": "https://adaptivecards.io/"
        },
        {
          "type": "Action.OpenUrl",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_three/assets/add_to_calendar_icon.png",
          "url": "https://adaptivecards.io/"
        },
        {
          "type": "Action.OpenUrl",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_three/assets/add_to_calendar_icon.png",
          "title": "Share in Teams",
          "mode": "secondary",
          "url": "https://adaptivecards.io/"
        },
        {
          "type": "Action.OpenUrl",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_three/assets/add_to_calendar_icon.png",
          "title": "Download",
          "url": "https://adaptivecards.io/",
          "mode": "secondary"
        },
        {
          "type": "Action.OpenUrl",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_three/assets/add_to_calendar_icon.png",
          "title": "Copy link",
          "mode": "secondary",
          "url": "https://adaptivecards.io/"
        }
      ]
    }
  ]
}
````

### Full width Card payload

````
{
  "type": "AdaptiveCard",
  "$schema": "http://adaptivecards.io/schemas/adaptive-card.json",
  "version": "1.5",
  "msTeams": {
    "width": "full"
  },
  "body": [
    {
      "type": "Image",
      "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_three/assets/video_image.png",
      "altText": "Web Development Bootcamp Video"
    },
    {
      "type": "TextBlock",
      "text": "Web Development Bootcamp",
      "wrap": true,
      "size": "Large",
      "weight": "Bolder"
    },
    {
      "type": "TextBlock",
      "text": "HackLab Films",
      "wrap": true,
      "spacing": "None",
      "weight": "Bolder"
    },
    {
      "type": "TextBlock",
      "text": "24m · 17.1M views · 2 months ago",
      "wrap": true,
      "spacing": "None"
    },
    {
      "type": "ActionSet",
      "targetWidth": "atLeast:narrow",
      "actions": [
        {
          "type": "Action.OpenUrl",
          "title": "Open",
          "url": "https://adaptivecards.io/"
        },
        {
          "type": "Action.OpenUrl",
          "title": "Add to calendar",
          "url": "https://adaptivecards.io/",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_three/assets/add_to_calendar_icon.png"
        },
        {
          "type": "Action.OpenUrl",
          "title": "Share in Teams",
          "mode": "secondary",
          "url": "https://adaptivecards.io/"
        },
        {
          "type": "Action.OpenUrl",
          "title": "Download",
          "url": "https://adaptivecards.io/",
          "mode": "secondary"
        },
        {
          "type": "Action.OpenUrl",
          "title": "Copy link",
          "mode": "secondary",
          "url": "https://adaptivecards.io/"
        }
      ]
    },
    {
      "type": "ActionSet",
      "targetWidth": "veryNarrow",
      "actions": [
        {
          "type": "Action.OpenUrl",
          "title": "Open",
          "url": "https://adaptivecards.io/"
        },
        {
          "type": "Action.OpenUrl",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_three/assets/add_to_calendar_icon.png",
          "url": "https://adaptivecards.io/"
        },
        {
          "type": "Action.OpenUrl",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_three/assets/add_to_calendar_icon.png",
          "title": "Share in Teams",
          "mode": "secondary",
          "url": "https://adaptivecards.io/"
        },
        {
          "type": "Action.OpenUrl",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_three/assets/add_to_calendar_icon.png",
          "title": "Download",
          "url": "https://adaptivecards.io/",
          "mode": "secondary"
        },
        {
          "type": "Action.OpenUrl",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_three/assets/add_to_calendar_icon.png",
          "title": "Copy link",
          "mode": "secondary",
          "url": "https://adaptivecards.io/"
        }
      ]
    }
  ]
}
````