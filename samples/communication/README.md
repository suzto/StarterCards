# Communication 

`need to update this page`

![picture alt](assets/CommsCard.png)

JSON from Adenin (See their sample here: https://app.adenin.com/app/designer/card/2170c936-8908-4e3d-a222-dd4cc2f4b4a9)




    JSON = 
     {
    "$schema": "http://adaptivecards.io/schemas/adaptive-card.json",
    "type": "AdaptiveCard",
    "version": "1.2",
    "body": [
        {
            "speak": "Tom's Pie is a Pizza restaurant which is rated 9.3 by customers.",
            "type": "ColumnSet",
            "columns": [
                {
                    "type": "Column",
                    "width": 4,
                    "items": [
                        {
                            "type": "ColumnSet",
                            "columns": [
                                {
                                    "type": "Column",
                                    "width": "auto",
                                    "items": [
                                        {
                                            "type": "Image",
                                            "url": "${published_avatar}",
                                            "size": "Small",
                                            "style": "Person"
                                        }
                                    ]
                                },
                                {
                                    "type": "Column",
                                    "width": "stretch",
                                    "items": [
                                        {
                                            "type": "TextBlock",
                                            "text": "**${published_by}** posted in ${category}",
                                            "size": "Small",
                                            "wrap": true,
                                            "maxLines": 3
                                        }
                                    ],
                                    "verticalContentAlignment": "Center"
                                }
                            ]
                        },
                        {
                            "type": "TextBlock",
                            "text": "${title}",
                            "weight": "Bolder",
                            "size": "ExtraLarge",
                            "wrap": true,
                            "maxLines": 3,
                            "spacing": "Small"
                        },
                        {
                            "type": "TextBlock",
                            "text": "${excerpt}",
                            "isSubtle": true,
                            "spacing": "None",
                            "wrap": true,
                            "maxLines": 4
                        }
                    ]
                },
                {
                    "type": "Column",
                    "width": 3,
                    "backgroundImage": {
                        "url": "https://www.adenin.com/assets/images/bg/office-scene.jpg",
                        "horizontalAlignment": "Center",
                        "verticalAlignment": "Center"
                    },
                    "spacing": "Medium"
                }
            ],
            "selectAction": {
                "type": "Action.OpenUrl",
                "id": "open-article",
                "url": "${title}"
            }
        },
        {
            "type": "ColumnSet",
            "columns": [
                {
                    "type": "Column",
                    "width": "auto",
                    "items": [
                        {
                            "type": "Image",
                            "url": "https://img.icons8.com/material-two-tone/48/000000/thumb-up--v1.png",
                            "width": "20px",
                            "spacing": "None",
                            "id": "Like"
                        },
                        {
                            "type": "Image",
                            "url": "data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHg9IjBweCIgeT0iMHB4Igp3aWR0aD0iNDgiIGhlaWdodD0iNDgiCnZpZXdCb3g9IjAgMCAxNzIgMTcyIgpzdHlsZT0iIGZpbGw6IzAwMDAwMDsiPjxnIGZpbGw9Im5vbmUiIGZpbGwtcnVsZT0ibm9uemVybyIgc3Ryb2tlPSJub25lIiBzdHJva2Utd2lkdGg9IjEiIHN0cm9rZS1saW5lY2FwPSJidXR0IiBzdHJva2UtbGluZWpvaW49Im1pdGVyIiBzdHJva2UtbWl0ZXJsaW1pdD0iMTAiIHN0cm9rZS1kYXNoYXJyYXk9IiIgc3Ryb2tlLWRhc2hvZmZzZXQ9IjAiIGZvbnQtZmFtaWx5PSJub25lIiBmb250LXdlaWdodD0ibm9uZSIgZm9udC1zaXplPSJub25lIiB0ZXh0LWFuY2hvcj0ibm9uZSIgc3R5bGU9Im1peC1ibGVuZC1tb2RlOiBub3JtYWwiPjxwYXRoIGQ9Ik0wLDE3MnYtMTcyaDE3MnYxNzJ6IiBmaWxsPSJub25lIj48L3BhdGg+PGcgZmlsbD0iIzM0OThkYiI+PHBhdGggZD0iTTE0LjMzMzMzLDcxLjY2NjY3aDQzdjcxLjY2NjY3aC00M3oiIG9wYWNpdHk9IjAuMyI+PC9wYXRoPjxwYXRoIGQ9Ik01MC4xNjY2Nyw2NC41aC00M3Y4Nmg0M2M3LjkxOTE3LDAgMTQuMzMzMzMsLTYuNDE0MTcgMTQuMzMzMzMsLTE0LjMzMzMzdi01Ny4zMzMzM2MwLC03LjkxOTE3IC02LjQxNDE3LC0xNC4zMzMzMyAtMTQuMzMzMzMsLTE0LjMzMzMzek01MC4xNjY2NywxMzYuMTY2NjdoLTI4LjY2NjY3di01Ny4zMzMzM2gyOC42NjY2N3oiPjwvcGF0aD48cGF0aCBkPSJNMTUwLjUsNTcuMzMzMzNoLTQ1LjUxNTVsNi43MDgsLTMwLjc4OGMxLjA0NjMzLC00LjgwODgzIC0wLjQ0NDMzLC05LjgxODMzIC0zLjk1NiwtMTMuMjY1NWwtNi4yMDYzMywtNi4xMTMxN2wtNDcuMTc4MTcsNDcuMjY0MTdjLTIuNjgwMzMsMi42ODc1IC00LjE4NTMzLDYuMzM1MzMgLTQuMTg1MzMsMTAuMTI2NXY3MS42MDkzM2MwLDcuOTE5MTcgNi40MTQxNywxNC4zMzMzMyAxNC4zMzMzMywxNC4zMzMzM2g2NC40NDk4M2M1LjcyNjE3LDAgMTAuOTA3NjcsLTMuNDExMzMgMTMuMTcyMzMsLTguNjc4ODNsMjEuNTUwMTcsLTUwLjE3MzgzYzAuNzY2ODMsLTEuNzg0NSAxLjE2MSwtMy43MTIzMyAxLjE2MSwtNS42NTQ1di0xNC4zMjYxN2MwLC03LjkxOTE3IC02LjQxNDE3LC0xNC4zMzMzMyAtMTQuMzMzMzMsLTE0LjMzMzMzek0xNTAuNSw4NS45OTI4M2wtMjEuNTUwMTcsNTAuMTczODNoLTY0LjQ0OTgzdi03MS42MDkzM2wzMS4wMTAxNywtMzEuMDY3NWwtNC41MjkzMywyMC43OTA1bC0zLjc4NCwxNy4zODYzM2gxNy43OTQ4M2g0NS41MDgzM3oiPjwvcGF0aD48L2c+PC9nPjwvc3ZnPg==",
                            "width": "20px",
                            "spacing": "None",
                            "isVisible": false,
                            "id": "LikeClicked"
                        }
                    ],
                    "verticalContentAlignment": "Center"
                },
                {
                    "type": "Column",
                    "width": "stretch",
                    "items": [
                        {
                            "type": "TextBlock",
                            "text": "${current_like_count} people like this",
                            "wrap": true,
                            "id": "CurrentLikes"
                        },
                        {
                            "type": "TextBlock",
                            "text": "${add(current_like_count, 1)} people like this",
                            "wrap": true,
                            "spacing": "None",
                            "isVisible": false,
                            "weight": "Bolder",
                            "id": "Liked"
                        }
                    ],
                    "verticalContentAlignment": "Center"
                },
                {
                    "type": "Column",
                    "width": "auto",
                    "items": [
                        {
                            "type": "ActionSet",
                            "actions": [
                                {
                                    "type": "Action.ToggleVisibility",
                                    "title": "Like",
                                    "targetElements": [
                                        "Like",
                                        "LikeClicked",
                                        "CurrentLikes",
                                        "Liked"
                                    ]
                                },
                                {
                                    "type": "Action.ToggleVisibility",
                                    "title": "Comment",
                                    "targetElements": [
                                        "CommentSection"
                                    ]
                                }
                            ]
                        }
                    ]
                }
            ]
        },
        {
            "type": "Container",
            "items": [
                {
                    "type": "Input.Text",
                    "placeholder": "What do you think?",
                    "id": "comment-field"
                },
                {
                    "type": "ActionSet",
                    "actions": [
                        {
                            "type": "Action.Submit",
                            "title": "Submit"
                        }
                    ]
                }
            ],
            "isVisible": false,
            "id": "CommentSection",
            "style": "emphasis"
        }
    ]
}
