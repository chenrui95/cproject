# 基础语法
## html文件中用到的内容
语法|作用|eg|备注
---|---|---|---
{{变量名}}|html中展示js中的变量值||文本插值
<html元素 v-bind:元素属性名="变量名">|将html的属性值设置为变量|```<h1 v-bind:color="color">```|
<html元素 v-if="变量名">|通过变量控制元素是否展示||相当于ngIf，变量为true展示，为false不展示
<html元素 v-for="单个变量 in 变量的list">|循环展示元素|```<li v-for="item in list">{{item.text}}</li>```|相当于ngFor="let item of list"
<html元素 v-on:事件名="方法名">|监听html元素的事件|```<button v-on:click="functionName">监听点击事件</button>```|相当于(onClick),(ngOnChange)等
<html元素 v-model="变量名">|html数据与js变量双向绑定||相当于[(ngModel)]="变量"

## 组件用到的内容
## 生命周期钩子
