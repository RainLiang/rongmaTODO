# rongmaTODO
一个中午的作品~~<br/>
基于Microsoft Excel 2013完成的任务管理系统<br/>
包含定时对话框提醒、 日常任务管理、完成度显示等功能<br/>
<br/><br/>
（BTW：仍然不够方便，限于目前技术水平较低，定时提醒功能需要手动输入代码才能完成）<br/><br/>

定时提醒功能的实现：<br/>
Alt+F11

在模块1输入代码：

Sub auto_open()
Application.OnTime TimeValue(弹出对话框的时间), "tx1"
End Sub

Sub tx1()
msg = MsgBox("对话框内容", vbInformation, "对话框标题")
End Sub






