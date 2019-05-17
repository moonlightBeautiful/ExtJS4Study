
信息提示对话框组件简介：Ext.window.MessageBox类
    有2个默认实例：Ext.MessageBox 和 Ext.Msg。只是名字不一样。
    常用5个方法：产生一个信息提示框实例
        alert()、confirm()、prompt()、wait()、show()
    信息提示框实例的常用方法：2个    
        updateText()：更新提示内容。
        updateProgress([Float value],[String progressText],[String msg])方法：更新进度条
               Float value：值为0-1，进度条初始长度比，1为满长度。
    其他常用方法：
        Ext.util.Format.date(new Date(), 'Y-m-d g:i:s A')：对日期进行格式化，并输出格式化后的日期
        Ext.TaskManager类：执行或者结束定时任务
            Ext.TaskManager.start(task);
            Ext.TaskManager.stop(task);
                var task = {
                	run:function(){	//执行函数,
                	interval:1000    //执行间隔,
                },