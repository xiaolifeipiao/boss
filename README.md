# Boss App

BOSS直聘APP-Vue 2.3.3版本

## 安装方法

``` bash
# 安装依赖库
npm install
cnpm install	#建议使用cpm安装

# 开发版启动预览 localhost:8080
npm run dev

# 打包生产环境
npm run build

# 使用分析报告打包预览
npm run build --report

# 运行单元测试
npm run unit

# 运行所有的测试脚本
npm test
```

## 文件结构

```shell
	     ┌── assets      资源文件
	     ├── components  页面以及组件
	     ├── js          插件和工具
	     ├── router      路由配置
	src──├── styles      页面样式
	     ├
	     ├── store      module/login：vuex登录session_id简单使用
	     ├
	     ├── App.vue 	页面
	     └── main.js  	页面配置入口
	        ┌── data    页面所需静态JOSON数据
	static──├── images  页面所需静态图片

```

## 在线体验

打开地址

### License

[MIT](http://opensource.org/licenses/MIT)


