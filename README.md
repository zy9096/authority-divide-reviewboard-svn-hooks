# authority-divide-reviewboard-svn-hooks
Devide experts to different repository instead of all paths.

Based on previous work by laiyonghao, the strict-review between svn and reviewboard is wonderful.
Howerver, the part of experts' authority seems to be unspecified that expert could ship any requests on reviewboard and
strict-review.py will not find the mistake.
In this project, the strict-review.py and the conf.ini was modified more specifiedly and the mistake was avoided successfully.  