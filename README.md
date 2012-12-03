# Copyright 2012 Google Inc.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

# Google Compute Engine JavaScript Sample Application

== Description
This is a simple web-based example of calling the Google Compute Engine API
in JavaScript.

## Setup Authentication
  NOTE: This README assumes that you have enabled access to the Google Compute
  Engine API via the Google API Console page.

  1) Visit https://code.google.com/apis/console/?api=compute to register your
  application.
    - Click on "API Access" in the left column
    - If you have not generated any client IDs, click the button labeled
    "Create an OAuth2 client ID...", otherwise, either select a previously
    created client ID, or click "Create another client ID..."
    - Give your application a name and click "Next"
    - Select "Web Application" as the "Application type"
    - Click "Create client ID"
    - Click "Edit settings..." for your new client ID
    - Under the redirect URI, enter the location of your JavaScript application
    - Under the JavaScript origin, enter the location of your JavaScript
    application
    - Click "Update"

  2) Update the following in app.html (projectId, clientId, apiKey).

## Running the Sample Application
  3) Load app.html on your web server, and visit the appropriate website in
  your web browser.
