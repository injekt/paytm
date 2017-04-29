# Dingtalk Paytm Homepage

This project is powered by [weex](https://weex.apache.org), which is an awesome solution for building [Dingtalk microapp](https://open-doc.dingtalk.com/docs/doc.htm?treeId=171&articleId=104910&docType=1) with extremely high performanece. 

Usually you can build your microapp in Dingtalk as a traditional webapp, however sometimes your users are unsatisfied with the poor performance of your webapp. Why? Nowadays the gap between web and native, in the aspect of performance and user experience, is still wide. You might feel frustrated to optimize the performance of your webapp, but finally bring just a little improvement. That is why we need weex.

With the help of weex, you can focus on your business, no more need to worry about the performance, just enjoy the fun of coding and building your microapp. The microapps based on weex will look so elegant and run so smoothly that your users cannot tell the difference between a weex microapp developed by javascript and a native user interface developed by java or objective-c.

The code you write for a weex microapp is javascript and css, you will feel so familiar if you are a web developer. Under the hood, weex render engine parse your code and render a completely native user interface, rather than a web user interface. 

You can refer to the doc of [weex](https://weex.apache.org/cn/) and [vue](https://cn.vuejs.org/) for more information.

Enjoy the fun of building dingtalk microapp with weex ☺

### Getting started

* Step 1: install dependencies
```npm install```

* Step 2: start a web server in dist directory 
```cd dist && python -m SimpleHTTPServer 8000```

* Step 3: start a dev build with auto hot reload
```npm run dev:weex```

* Step 4: open your weex microapp in Dingtalk app. 

  * 4.1: send a message to yourself in Dingtalk app with this url:
```http://{your LAN ip}:8000?dd_wx_tpl=http://{your LAN ip}/dist/weex-bundle.js```

  * 4.2: click the url message and open the weex microapp


### Setting up your dingtalk homepage

* Step 1: log in [https://oa.dingtalk.com](https://oa.dingtalk.com)
* Step 2: find "Enterprise Application" on top nav bar
* Step 3: find "Workbench Setting" on left nav bar
* Step 4: choose "Link the company's existing home page" on main panel
* Step 5: enter your weex page url as above and click "Save"
