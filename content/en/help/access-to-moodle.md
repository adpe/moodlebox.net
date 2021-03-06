---
title: How to log into the Moodle site of the MoodleBox
authors:
  - Nicolas Martignoni
type: kb
date: 2017-04-20
lastmod: 2018-10-24
description: To access to the Moodle installation of the MoodleBox, you must be connected to its Wi-Fi network and open http://moodlebox.home/
slug: access-to-moodle
weight: 6
categories:
  - Usage

---
To access to the Moodle installation of the MoodleBox, you must be [connected to its Wi-Fi network][1]. On your device, choose __MoodleBox__ wireless network. When prompted type the password: __moodlebox__ (all lowercase) and confirm your connection.

You may now log into Moodle in your browser. Open your browser and type [http://moodlebox.home/][2] in the address bar. The home page of Moodle opens. Click on __Log in__ and type the following credentials:

  * username: __moodlebox__
  * password: __Moodlebox4$__

{{% notice info %}}
The username __admin__ (with the same password __Moodlebox4$__), used up to version 2.5.1 of the MoodleBox, is still valid, but is no longer recommended. It will be removed in a future version of the image.
{{% /notice %}}

{{< figure src="/img/media/moodle-login-en.png" caption="Moodle Login" caption-position="bottom" caption-effect="appear" width="610px" >}}

You're now logged into the Moodle administrator account of the MoodleBox. It's __strongly recommended that you change the default password__ of the Moodle admin account at the first login.

The initial Moodle installation has only one account (administrator) and no course is created. The Moodle environment should be configured by yourself, as well as the management of its contents (resources, activities, etc.). See the [Moodle documentation][3] if you don't know how to do this.

 [1]: {{< relref "wi-fi-connection.md" >}}
 [2]: http://moodlebox.home/
 [3]: https://docs.moodle.org/en/Admin_quick_guide
