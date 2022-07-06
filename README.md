# automation-seleniumide-test
QA Assessment ProSpark

{
  "id": "11d2a5fd-229f-414f-9736-7d7627c639a0",
  "version": "2.0",
  "name": "ProSpark Test",
  "url": "https://demos2.prospark.co",
  "tests": [{
    "id": "2ad549dd-863f-4265-9c63-44f3effe48cb",
    "name": "Automation test",
    "commands": [{
      "id": "9f1146ce-fb3d-426e-8c95-d9e4e120f1c3",
      "comment": "",
      "command": "open",
      "target": "/adminspark/dashboard",
      "targets": [],
      "value": ""
    }, {
      "id": "db34bab4-0d0d-4458-ba69-dd595beef6c1",
      "comment": "",
      "command": "setWindowSize",
      "target": "1062x662",
      "targets": [],
      "value": ""
    }, {
      "id": "085e1f51-4855-4f87-9a76-1091cbabf9b0",
      "comment": "",
      "command": "open",
      "target": "https://demos2.prospark.co/adminspark/user/learners#",
      "targets": [],
      "value": ""
    }, {
      "id": "046dcb4a-af31-42f7-9f9b-6d19c98b3406",
      "comment": "",
      "command": "click",
      "target": "css=.m-dropdown__toggle",
      "targets": [
        ["css=.m-dropdown__toggle", "css:finder"],
        ["xpath=//li/div/button", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "8a64cca7-a9ba-4efa-b563-c46a17af1785",
      "comment": "",
      "command": "click",
      "target": "css=.m-nav__item:nth-child(1) .text-black",
      "targets": [
        ["css=.m-nav__item:nth-child(1) .text-black", "css:finder"],
        ["xpath=//div/div/div/div/div/ul/li/a/span", "xpath:position"],
        ["xpath=//span[contains(.,'Create User')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "62550a75-3074-4271-89c4-fa96d764d2dd",
      "comment": "",
      "command": "click",
      "target": "id=firstname",
      "targets": [
        ["id=firstname", "id"],
        ["name=firstname", "name"],
        ["css=#firstname", "css:finder"],
        ["xpath=//input[@id='firstname']", "xpath:attributes"],
        ["xpath=//form[@id='createUserForm']/div/div/div/div/div/input", "xpath:idRelative"],
        ["xpath=//div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "f3bc67fd-f4ca-416c-b3dc-47a3f2a068d0",
      "comment": "",
      "command": "type",
      "target": "id=firstname",
      "targets": [
        ["id=firstname", "id"],
        ["name=firstname", "name"],
        ["css=#firstname", "css:finder"],
        ["xpath=//input[@id='firstname']", "xpath:attributes"],
        ["xpath=//form[@id='createUserForm']/div/div/div/div/div/input", "xpath:idRelative"],
        ["xpath=//div/input", "xpath:position"]
      ],
      "value": "Check"
    }, {
      "id": "e8ff5184-819f-4d1b-a21c-1e98d22c1782",
      "comment": "",
      "command": "click",
      "target": "id=lastname",
      "targets": [
        ["id=lastname", "id"],
        ["name=lastname", "name"],
        ["css=#lastname", "css:finder"],
        ["xpath=//input[@id='lastname']", "xpath:attributes"],
        ["xpath=//form[@id='createUserForm']/div/div/div/div/div[2]/input", "xpath:idRelative"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "3605b6c7-0b3f-44a3-b92d-667f8a4918dd",
      "comment": "",
      "command": "type",
      "target": "id=lastname",
      "targets": [
        ["id=lastname", "id"],
        ["name=lastname", "name"],
        ["css=#lastname", "css:finder"],
        ["xpath=//input[@id='lastname']", "xpath:attributes"],
        ["xpath=//form[@id='createUserForm']/div/div/div/div/div[2]/input", "xpath:idRelative"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": "Automation"
    }, {
      "id": "a79af70f-3c60-4edf-b109-2d542d2a4717",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["name=email", "name"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//form[@id='createUserForm']/div/div/div/div/div[3]/input", "xpath:idRelative"],
        ["xpath=//div[3]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "6603bd65-8372-4ec4-a4a2-8f4265daf253",
      "comment": "",
      "command": "type",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["name=email", "name"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//form[@id='createUserForm']/div/div/div/div/div[3]/input", "xpath:idRelative"],
        ["xpath=//div[3]/input", "xpath:position"]
      ],
      "value": "automation@yyy.com"
    }, {
      "id": "0df585a0-d250-40cd-a6cd-60c40c9c7574",
      "comment": "",
      "command": "click",
      "target": "id=gender",
      "targets": [
        ["id=gender", "id"],
        ["name=gender", "name"],
        ["css=#gender", "css:finder"],
        ["xpath=//select[@id='gender']", "xpath:attributes"],
        ["xpath=//form[@id='createUserForm']/div/div/div/div[2]/div[2]/div/select", "xpath:idRelative"],
        ["xpath=//select", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "b91590c9-2c37-4c83-bff1-d6a50d492167",
      "comment": "",
      "command": "select",
      "target": "id=gender",
      "targets": [],
      "value": "label=Female"
    }, {
      "id": "e590e9ba-c17f-40ea-a80e-15fc3f4f093b",
      "comment": "",
      "command": "click",
      "target": "id=username",
      "targets": [
        ["id=username", "id"],
        ["name=username", "name"],
        ["css=#username", "css:finder"],
        ["xpath=//input[@id='username']", "xpath:attributes"],
        ["xpath=//form[@id='createUserForm']/div/div/div[2]/div/div/input", "xpath:idRelative"],
        ["xpath=//form/div/div/div[2]/div/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "58156988-c29a-4b41-bb66-9ba9484da643",
      "comment": "",
      "command": "type",
      "target": "id=username",
      "targets": [
        ["id=username", "id"],
        ["name=username", "name"],
        ["css=#username", "css:finder"],
        ["xpath=//input[@id='username']", "xpath:attributes"],
        ["xpath=//form[@id='createUserForm']/div/div/div[2]/div/div/input", "xpath:idRelative"],
        ["xpath=//form/div/div/div[2]/div/div/input", "xpath:position"]
      ],
      "value": "automation01"
    }, {
      "id": "8ec7ad3a-cfcf-4233-8240-92b0006ceb78",
      "comment": "",
      "command": "click",
      "target": "id=password",
      "targets": [
        ["id=password", "id"],
        ["name=password", "name"],
        ["css=#password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//form[@id='createUserForm']/div/div/div[2]/div[2]/div/input", "xpath:idRelative"],
        ["xpath=//div[2]/div[2]/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "e345f85a-28d6-4df9-9413-78a69d9e1063",
      "comment": "",
      "command": "type",
      "target": "id=password",
      "targets": [],
      "value": "Bunny2195"
    }, {
      "id": "f2d35fe7-04da-4b14-9318-8bf43d770e68",
      "comment": "",
      "command": "click",
      "target": "id=password_confirmation",
      "targets": [
        ["id=password_confirmation", "id"],
        ["name=password_confirmation", "name"],
        ["css=#password_confirmation", "css:finder"],
        ["xpath=//input[@id='password_confirmation']", "xpath:attributes"],
        ["xpath=//form[@id='createUserForm']/div/div/div[2]/div[3]/div/input", "xpath:idRelative"],
        ["xpath=//div[3]/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "0160802a-9af4-4b20-8578-b1deb7b7f04b",
      "comment": "",
      "command": "type",
      "target": "id=password_confirmation",
      "targets": [
        ["id=password_confirmation", "id"],
        ["name=password_confirmation", "name"],
        ["css=#password_confirmation", "css:finder"],
        ["xpath=//input[@id='password_confirmation']", "xpath:attributes"],
        ["xpath=//form[@id='createUserForm']/div/div/div[2]/div[3]/div/input", "xpath:idRelative"],
        ["xpath=//div[3]/div/input", "xpath:position"]
      ],
      "value": "Bunny2195"
    }, {
      "id": "ba55baf3-b674-4638-8369-198aa67c97f0",
      "comment": "",
      "command": "click",
      "target": "id=role_id",
      "targets": [
        ["id=role_id", "id"],
        ["name=role_id", "name"],
        ["css=#role_id", "css:finder"],
        ["xpath=//select[@id='role_id']", "xpath:attributes"],
        ["xpath=//form[@id='createUserForm']/div/div/div[3]/div[2]/div/div/div/select", "xpath:idRelative"],
        ["xpath=//div[2]/div/div/div/select", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "2786832f-435e-40e7-bbe6-db368e5c470f",
      "comment": "",
      "command": "select",
      "target": "id=role_id",
      "targets": [],
      "value": "label=Learner"
    }, {
      "id": "c6a14d64-c4d1-4f22-a54c-7fdf06a78a23",
      "comment": "",
      "command": "click",
      "target": "id=function_id",
      "targets": [
        ["id=function_id", "id"],
        ["name=function_id", "name"],
        ["css=#function_id", "css:finder"],
        ["xpath=//select[@id='function_id']", "xpath:attributes"],
        ["xpath=//form[@id='createUserForm']/div/div/div[3]/div[2]/div[2]/div/div/select", "xpath:idRelative"],
        ["xpath=//div[2]/div[2]/div/div/select", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "2131e0b3-beca-4b61-abbc-4e46273dfdb0",
      "comment": "",
      "command": "select",
      "target": "id=function_id",
      "targets": [],
      "value": "label=default"
    }, {
      "id": "28ab4d21-348f-47a8-ad7e-4cd671bef686",
      "comment": "",
      "command": "click",
      "target": "id=btnCreateUser",
      "targets": [
        ["id=btnCreateUser", "id"],
        ["css=#btnCreateUser", "css:finder"],
        ["xpath=//button[@id='btnCreateUser']", "xpath:attributes"],
        ["xpath=//form[@id='createUserForm']/div/div/div[3]/div[3]/ul/li[2]/button", "xpath:idRelative"],
        ["xpath=//li[2]/button", "xpath:position"],
        ["xpath=//button[contains(.,'Submit')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "bd5a995e-198f-443f-bdbd-0a70f4f4e33d",
      "comment": "",
      "command": "verifyText",
      "target": "css=.alert",
      "targets": [
        ["css=.alert", "css:finder"],
        ["xpath=//div[2]/div/div/div[3]/div/div", "xpath:position"]
      ],
      "value": "Heads up! User successfully created!"
    }]
  }],
  "suites": [{
    "id": "d7b7b6fc-de8c-4f2a-a42c-8d7404ae86a3",
    "name": "Default Suite",
    "persistSession": false,
    "parallel": false,
    "timeout": 300,
    "tests": ["2ad549dd-863f-4265-9c63-44f3effe48cb"]
  }],
  "urls": ["https://demos2.prospark.co/"],
  "plugins": []
}
