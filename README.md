# pop
pop消息弹窗
本弹窗插件主要提供四种形式的操作交互与提示：
 1.alert:操作完成后的提示弹窗，调用方法：pop.alert(msg,type,fun)，msg为提示信息，type可取值'success'/'fail'/'warning'/'smile'，fun为倒计时3秒后执行的函数体
 2.confirm:确定或取消交互弹窗，调用方法：pop.confirm(msg,fun)，msg为提示信息，fun为点击弹窗中的 确定 按钮后执行的函数体
 3.open:操作进行时的警示弹窗，调用方法：pop.open(msg,type,fun)，msg为提示信息，type可取值'success'/'fail'/'warning'/'smile'，fun为点击弹窗中的 确定 按钮后执行的函数体
 4.prompt:响应事件后的简短消息提示，比如表单验证blur事件后的错误提示，调用方法：pop.prompt(msg,target,time), msg为提示信息，target为要插入到的目标元素，留空则插入body并居中显示，time为提示窗口显示的时间，留空则默认为1.5s
 另外：以上参数中msg为必填，type/fun为选填，但是如果要填就必须按照 msg>type>fun 这样的顺序
