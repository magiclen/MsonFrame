MsonFrame
=================================

# Introduction

**MsonFrame** is an JavaFX application, which used [**Mson**](https://github.com/magiclen/MagicLenJSON "Mson") to convert JSON formatted strings to XML formatted strings, and to convert XML formatted strings back to JSON formatted strings. More over, if you think your JSON formatted strings are not instinctive, you can use this application to help you format the strings with a pretty form.

# Usage

##### 1. Run the program file named **MsonFrame.jar**. #####
##### 2. Input some texts you want to convert. For example, #####

       {"website":"http://magiclen.org","authors":[{"birthday":[1993,8,10],"phone":[88693929304,"041112233"],"name":"Magic Len","id":1,"lang":"繁體中文"},{"birthday":[1991,1,1],"name":"Dean ML","phones":["711423000","556432234"],"id":2,"lang":"English"}]}

##### 3. The conversion's result will be, #####

    {
        "website" : "http://magiclen.org",
        "authors" : [
            {
                "birthday" : [
                    1993,
                    8,
                    10
                ],
                "phone" : [
                    88693929304,
                    "041112233"
                ],
                "name" : "Magic Len",
                "id" : 1,
                "lang" : "繁體中文"
            },
            {
                "birthday" : [
                    1991,
                    1,
                    1
                ],
                "name" : "Dean ML",
                "phones" : [
                    "711423000",
                    "556432234"
                ],
                "id" : 2,
                "lang" : "English"
            }
        ]
    }

    ----------------

    <website>http://magiclen.org</website><authors><birthday>1993</birthday><birthday>8</birthday><birthday>10</birthday><phone>88693929304</phone><phone>041112233</phone><name>Magic Len</name><id>1</id><lang>繁體中文</lang></authors><authors><birthday>1991</birthday><birthday>1</birthday><birthday>1</birthday><name>Dean ML</name><phones>711423000</phones><phones>556432234</phones><id>2</id><lang>English</lang></authors>

##### 4. Click the **copy** button to copy the result to your clipboard. #####

# License

    Copyright 2015 magiclen.org

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

# What's More?

Please check out our web page at

http://magiclen.org/mson-frame/
