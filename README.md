基于omni的4.4分支的2.7.1.0版TWRP汉化
graphics_cn.c和中文字库为从前人已经汉化过的2.5版中提取
2.6、2.7版之前的ui.xml内容参照了前人已经汉化过的2.5版的ui.xml
2.6、2.7版ui.xml新添加的内容为本人汉化，可能会有不足之处
我只汉化了720x1280和1080x1920的ui.xml，其他分辨率的ui.xml请自行用BC对比汉化，很快的




**Team Win Recovery Project (TWRP)**

The goal of this branch is to rebase TWRP onto AOSP while maintaining as much of the original AOSP code as possible. This goal should allow us to apply updates to the AOSP code going forward with little to no extra work.  With this goal in mind, we will carefully consider any changes needed to the AOSP code before allowing them.  In most cases, instead of changing the AOSP code, we'll create our own functions instead.  The only changes that should be made to AOSP code should be those affecting startup of the recovery and some of the make files.

If there are changes that need to be merged from AOSP, we will pull the change directly from AOSP instead of creating a new patch in order to prevent merge conflicts with AOSP.

This branch is under final testing and will be used shortly for public builds, but has not officially been released.

You can find a compiling guide [here](http://forum.xda-developers.com/showthread.php?t=1943625 "Guide").

[More information about the project.](http://www.teamw.in/project/twrp2 "More Information")

If you have code changes to submit those should be pushed to our gerrit instance.  A guide can be found [here](http://teamw.in/twrp2-gerrit "Gerrit Guide").
