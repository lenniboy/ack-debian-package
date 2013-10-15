# ack Debian package

These scripts allow you to build a debian package for ack2 using the standlaone distribution

## Building the debian package

To build the package simply, `debuild -S -sd` from this project root directory.

To upload it to the PPA `dput ppa:leonard-ehrenfried/ack2 ack-grep_2.10-1_source.changes`

## Licence

This software is licensed under the Apache 2 license, quoted below.

Copyright 2013 Leonard Ehrenfried (http://leonard.io).

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this project except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0.

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
