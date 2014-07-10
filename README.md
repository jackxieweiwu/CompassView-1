CompassView
===========

Compass view for Android.

This library provides a fully customizable linear compass view.

![image](screenshot1.jpg)

## Usage
You can declare a `CompassView` just like that:

```XML
<com.redinput.compassview.CompassView
    android:id="@+id/compass"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    app:backgroundColor="#000000"
    app:showMarker="true"
    app:markerColor="#FF0000"
    app:lineColor="#FFFFFF"
    app:textColor="#FFFFFF"
    app:textSize="15sp"
    app:degrees="0"
    app:rangeDegrees="180.0" />
```

Property values shown above are the defaults of the CompassView and could be omitted for brevity.

Also, you can set the degrees value with Java.

```JAVA
CompassView compass = (CompassView) findViewById(R.id.compass);

// It accepts Float and Integer as degrees values  
compass.setDegrees(57);
compass.setDegrees(123.54);
```

License
-------
    Copyright 2014 RedInput

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.