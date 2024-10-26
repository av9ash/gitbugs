**Download Link**
https://drive.google.com/file/d/1yzKHQgejkt9pHRRvjp3nhDphKKpVRdEm/view?usp=sharing

**HOW TO USE**

Upload the json zip file to your google drive and **change** the "%cd /gdrive/MyDrive/Colab\ Notebooks" in the below notebook.

**How to Use**: Following Notebook will load the original bugs from json, make them into a vectors using TFIDF and search top n neighbors using SKlearn Nearest Neighbors 
https://colab.research.google.com/drive/1Uc9hTvBAjdF7oalpk2zoq7QJO6q7mzq6?usp=sharing

https://medium.com/@avinash.patil.0909/duplicate-bug-reports-detection-using-ml-925ef6409394

**About**
The data set has 32829 records. 
Below is a json sample of all the information that is being captured.
Date Range Oct2015 - Jul2024

{
        "url": "https://api.github.com/repos/microsoft/vscode/issues/223706",
        "repository_url": "https://api.github.com/repos/microsoft/vscode",
        "labels_url": "https://api.github.com/repos/microsoft/vscode/issues/223706/labels{/name}",
        "comments_url": "https://api.github.com/repos/microsoft/vscode/issues/223706/comments",
        "events_url": "https://api.github.com/repos/microsoft/vscode/issues/223706/events",
        "html_url": "https://github.com/microsoft/vscode/issues/223706",
        "id": 2430137242,
        "node_id": "I_kwDOAn8RLM6Q2POa",
        "number": 223706,
        "title": "Configure unassigned keybindings, command name incorrect",
        "user": {
            "login": "aiday-mar",
            "id": 61460952,
            "node_id": "MDQ6VXNlcjYxNDYwOTUy",
            "avatar_url": "https://avatars.githubusercontent.com/u/61460952?v=4",
            "gravatar_id": "",
            "url": "https://api.github.com/users/aiday-mar",
            "html_url": "https://github.com/aiday-mar",
            "followers_url": "https://api.github.com/users/aiday-mar/followers",
            "following_url": "https://api.github.com/users/aiday-mar/following{/other_user}",
            "gists_url": "https://api.github.com/users/aiday-mar/gists{/gist_id}",
            "starred_url": "https://api.github.com/users/aiday-mar/starred{/owner}{/repo}",
            "subscriptions_url": "https://api.github.com/users/aiday-mar/subscriptions",
            "organizations_url": "https://api.github.com/users/aiday-mar/orgs",
            "repos_url": "https://api.github.com/users/aiday-mar/repos",
            "events_url": "https://api.github.com/users/aiday-mar/events{/privacy}",
            "received_events_url": "https://api.github.com/users/aiday-mar/received_events",
            "type": "User",
            "site_admin": false
        },
        "labels": [
            {
                "id": 256129993,
                "node_id": "MDU6TGFiZWwyNTYxMjk5OTM=",
                "url": "https://api.github.com/repos/microsoft/vscode/labels/bug",
                "name": "bug",
                "color": "8D6673",
                "default": true,
                "description": "Issue identified by VS Code Team member as probable bug"
            },
            {
                "id": 316813364,
                "node_id": "MDU6TGFiZWwzMTY4MTMzNjQ=",
                "url": "https://api.github.com/repos/microsoft/vscode/labels/accessibility",
                "name": "accessibility",
                "color": "d93f0b",
                "default": false,
                "description": "Keyboard, mouse, ARIA, vision, screen readers (non-specific) issues"
            }
        ],
        "state": "open",
        "locked": false,
        "assignee": {
            "login": "meganrogge",
            "id": 29464607,
            "node_id": "MDQ6VXNlcjI5NDY0NjA3",
            "avatar_url": "https://avatars.githubusercontent.com/u/29464607?v=4",
            "gravatar_id": "",
            "url": "https://api.github.com/users/meganrogge",
            "html_url": "https://github.com/meganrogge",
            "followers_url": "https://api.github.com/users/meganrogge/followers",
            "following_url": "https://api.github.com/users/meganrogge/following{/other_user}",
            "gists_url": "https://api.github.com/users/meganrogge/gists{/gist_id}",
            "starred_url": "https://api.github.com/users/meganrogge/starred{/owner}{/repo}",
            "subscriptions_url": "https://api.github.com/users/meganrogge/subscriptions",
            "organizations_url": "https://api.github.com/users/meganrogge/orgs",
            "repos_url": "https://api.github.com/users/meganrogge/repos",
            "events_url": "https://api.github.com/users/meganrogge/events{/privacy}",
            "received_events_url": "https://api.github.com/users/meganrogge/received_events",
            "type": "User",
            "site_admin": true
        },
        "assignees": [
            {
                "login": "meganrogge",
                "id": 29464607,
                "node_id": "MDQ6VXNlcjI5NDY0NjA3",
                "avatar_url": "https://avatars.githubusercontent.com/u/29464607?v=4",
                "gravatar_id": "",
                "url": "https://api.github.com/users/meganrogge",
                "html_url": "https://github.com/meganrogge",
                "followers_url": "https://api.github.com/users/meganrogge/followers",
                "following_url": "https://api.github.com/users/meganrogge/following{/other_user}",
                "gists_url": "https://api.github.com/users/meganrogge/gists{/gist_id}",
                "starred_url": "https://api.github.com/users/meganrogge/starred{/owner}{/repo}",
                "subscriptions_url": "https://api.github.com/users/meganrogge/subscriptions",
                "organizations_url": "https://api.github.com/users/meganrogge/orgs",
                "repos_url": "https://api.github.com/users/meganrogge/repos",
                "events_url": "https://api.github.com/users/meganrogge/events{/privacy}",
                "received_events_url": "https://api.github.com/users/meganrogge/received_events",
                "type": "User",
                "site_admin": true
            }
        ],
        "milestone": {
            "url": "https://api.github.com/repos/microsoft/vscode/milestones/275",
            "html_url": "https://github.com/microsoft/vscode/milestone/275",
            "labels_url": "https://api.github.com/repos/microsoft/vscode/milestones/275/labels",
            "id": 11245511,
            "node_id": "MI_kwDOAn8RLM4Aq5fH",
            "number": 275,
            "title": "August 2024",
            "description": "",
            "creator": {
                "login": "Yoyokrazy",
                "id": 12552271,
                "node_id": "MDQ6VXNlcjEyNTUyMjcx",
                "avatar_url": "https://avatars.githubusercontent.com/u/12552271?v=4",
                "gravatar_id": "",
                "url": "https://api.github.com/users/Yoyokrazy",
                "html_url": "https://github.com/Yoyokrazy",
                "followers_url": "https://api.github.com/users/Yoyokrazy/followers",
                "following_url": "https://api.github.com/users/Yoyokrazy/following{/other_user}",
                "gists_url": "https://api.github.com/users/Yoyokrazy/gists{/gist_id}",
                "starred_url": "https://api.github.com/users/Yoyokrazy/starred{/owner}{/repo}",
                "subscriptions_url": "https://api.github.com/users/Yoyokrazy/subscriptions",
                "organizations_url": "https://api.github.com/users/Yoyokrazy/orgs",
                "repos_url": "https://api.github.com/users/Yoyokrazy/repos",
                "events_url": "https://api.github.com/users/Yoyokrazy/events{/privacy}",
                "received_events_url": "https://api.github.com/users/Yoyokrazy/received_events",
                "type": "User",
                "site_admin": false
            },
            "open_issues": 289,
            "closed_issues": 3,
            "state": "open",
            "created_at": "2024-06-28T00:13:29Z",
            "updated_at": "2024-07-25T23:24:33Z",
            "due_on": "2024-09-06T07:00:00Z",
            "closed_at": null
        },
        "comments": 1,
        "created_at": "2024-07-25T14:34:59Z",
        "updated_at": "2024-07-25T16:20:47Z",
        "closed_at": null,
        "author_association": "CONTRIBUTOR",
        "active_lock_reason": null,
        "body": "- Place cursor in the panel chat\r\n- Open the accessibility help\r\n- Click on the icon `Accessibility Help Configure Unassigned Keybindings`\r\n- The command list does not contain actual command names\r\n\r\n\r\nhttps://github.com/user-attachments/assets/73b8b4da-2bdf-4664-9d47-7c7d2bde73a0\r\n\r\n",
        "reactions": {
            "url": "https://api.github.com/repos/microsoft/vscode/issues/223706/reactions",
            "total_count": 0,
            "+1": 0,
            "-1": 0,
            "laugh": 0,
            "hooray": 0,
            "confused": 0,
            "heart": 0,
            "rocket": 0,
            "eyes": 0
        },
        "timeline_url": "https://api.github.com/repos/microsoft/vscode/issues/223706/timeline",
        "performed_via_github_app": null,
        "state_reason": null
    }

