# Bootstrap Multiselect

Bootstrap Multiselect is a JQuery based plugin to provide an intuitive user interface for using select inputs with the multiple attribute present. Instead of a select a bootstrap button will be shown w dropdown menu containing the single options as checkboxes.

This project is a fork of http://davidstutz.github.io/bootstrap-multiselect/

Link to original project documentation -> [http://davidstutz.github.io/bootstrap-multiselect/](http://davidstutz.github.io/bootstrap-multiselect/).

![Example of a multiselect.](example.png?raw=true "Example of a multiselect.")

## Additions

Few options has been add : 
    - includeSelectNoneOption
    - selectNoneJustVisible
    - selectNoneText
    - selectNoneValue
    - selectNoneName
    - includeSelectAllDivider 
    - includeSelectNoneDivider

### includeSelectNoneOption

Set to `true` or `false` to enable or disable the select none option.

```javascript
$('#my-multiselect').multiselect({
            includeSelectAllOption: true
})
```
The `includeSelectNoneOption` option can also be used in combination with `optgroup`'s and `includeSelectAllOption`.
Note that the select none does not trigger the onChange event and only triggers the `onDeselectAll` event

### selectNoneJustVisible

Setting both `includeSelectNoneOption` and `enableFiltering` to `true`, the select none option does always deselect only the visible option. With setting `selectNoneJustVisible` to `false` this behavior is changed such that always all options (irrespective of whether they are visible) are deselected.

## License

**Apache License, Version 2.0**

Copyright (c) 2012 - 2015 David Stutz

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

**BSD 3-Clause License**

Copyright (c) 2012 - 2015 David Stutz
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
* Neither the name of David Stutz nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
