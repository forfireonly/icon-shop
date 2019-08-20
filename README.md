# Implementation of local differential privacy for android app with  Google Analytics/Firebase

Following [codelab tutorial.](https://codelabs.developers.google.com/codelabs/firebase-analytics/index.html?index=..%2F..index#0), I have implemented Google Analytics with Firebase. I was able to log in analytics events in a sample android app.

![IconshopApp](https://user-images.githubusercontent.com/29640816/63233808-796c5c80-c1ef-11e9-99cb-39d18c93f8a8.gif)
![FirebaseDashboard](https://user-images.githubusercontent.com/29640816/63233817-84bf8800-c1ef-11e9-87d9-99c5e375adee.gif)
<img width="1574" alt="FirebaseEvents" src="https://user-images.githubusercontent.com/29640816/63233821-8d17c300-c1ef-11e9-90ac-62fade665b80.png">

From [https://firebase.google.com/support/privacy] "Firebase customers typically act as the "data controller" for any personal data about their end-users they provide to Google in connection with their use of Firebase, and Google is, generally, a "data processor".
This means that data is under the customer's control. Controllers are responsible for obligations like fulfilling an individual's rights with respect to their personal data."

To be able to use Google Analytics I as developer have to make sure that I have the right consents in place for users who download my app.

I have decided to explore the possibility of offering app users local differential privacy.



### License

```
Copyright 2016 Google, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements. See the NOTICE file distributed with this work for
additional information regarding copyright ownership. The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License. You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
License for the specific language governing permissions and limitations under
the License.
```
