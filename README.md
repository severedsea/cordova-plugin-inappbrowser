<!---
 license: Licensed to the Apache Software Foundation (ASF) under one
         or more contributor license agreements.  See the NOTICE file
         distributed with this work for additional information
         regarding copyright ownership.  The ASF licenses this file
         to you under the Apache License, Version 2.0 (the
         "License"); you may not use this file except in compliance
         with the License.  You may obtain a copy of the License at

           http://www.apache.org/licenses/LICENSE-2.0

         Unless required by applicable law or agreed to in writing,
         software distributed under the License is distributed on an
         "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
         KIND, either express or implied.  See the License for the
         specific language governing permissions and limitations
         under the License.
-->

# org.apache.cordova.inappbrowser

Plugin documentation: [doc/index.md](doc/index.md)

(iOS and Android only)
Added InAppBrowser option "clearsocialnetworkcookie" through window.open that clears InAppBrowser social network cookies specifically: 

1. facebook.com
2. linkedin.com
3. twitter.com

## Usage

    // Clears social network cookies on InAppBrowser open.
    var window.open(url, name, 'clearsocialnetworkcookie=yes');


Hopefully, this can be extended to a more generic way of clearing cache by providing domains as arguments in InAppBrowser through window.open options. 