## ExpanDialog

Wellcome to this page , there is my first library for Android -- ExpandDialog

It like the AlertDialog, but I let it come form top and buttom with an anim. 

![Screenshot](https://github.com/XandyWang/ExpandDialog/raw/master/screenshot/s.jpg)

----------

You can use like this 


``` Java

ExpandDialog.Builder mBuilder = new ExpandDialog.Builder(mContext);
mBuilder.setTitle("Expand Dialog");
mBuilder.setCanceledOnTouchOutside(false)
mBuilder.setGravity(Gravity.BOTTOM);
mBuilder.setMultiChoiceItems(
				new String[]{"1","2","3","4","5","6","7","8","9","10","11","12"}, 
				new boolean[]{false,true,true,false,true,true,false,true,true,false,true,true}, 
				null);
ExpandDialog dialog = mBuilder.create();
dialog.show();

```

This is a MultiChoice dialog , you can use is as AlertDialog.

License
===

   Copyright 2013 Issac Wong

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

