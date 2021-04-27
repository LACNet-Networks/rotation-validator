# Rotation Validator

This component is a client used to rotate the validator nodes in LACChain network. To know more about this solution, please check this [documentation](docs/Architecture.md).

## Prerequisites

* Being a validator node in LACChain network
* Go 1.13+ installation or later
* **GOPATH** environment variable is set correctly

## Install

```
$ git clone https://github.com/lacchain/rotation-validator

$ cd rotation-validator
$ go build
```

## Run

Execute the executable file generated previously in a Validator node

```
$ ./rotation-validator
```

## Copyright 2020 LACChain

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.