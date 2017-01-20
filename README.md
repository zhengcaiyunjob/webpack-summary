# webpack-summary
##1. 关于loaders:
    loaders可以理解为我们所写的各类文件的程序转换器，负责将各类文件类型转换为浏览器可以识别和运行的程序文件。
    在webpack的官网上，根据各类文件类型的不同，划分出了各种类型的loaders。
        主要包括：
                1. basic -> 包括文件中一些特殊类型的编译（svg, base64,glsl等）及一些特殊语法的编译。例如：$=jquery => var $ = require("jquery");
                2. packaging -> 该部分的loader主要用来做各种打包处理。 
                3. dialects-> 对各类语法的编译， 例如coffee-script,jsx,sweetjs.
                4. templating->对各类模板的处理。例如dom-loader将所有的html模板放到另外一个DOM element中。
                5. styling-> 类似的对各种样式文件的处理，例如less,sass，css,cess等。
                6. translation->
                7. support -> 类似小工具的功能，例如预编译功能。
##2. 关于plugins：
    在webpack中使用插件可以帮助我们在构建的过程中实现一些其他的功能，比如说使用 BellOnBundlerErrorPlugin插件，可以帮助我们排查构建过程中的一些错误。官网上根据插件的使用功能的差异划分为以下几类：
    主要包括：
            1. config ->配置类，例如ignorPlugin, ResolverPlugin,EnvironmentPlugin等。
            2. output ->输出类插件
            3. optimize ->优化类插件
            4. localization-> 就是将一些
            5. debugging ->
            6. other->
##3. 关于devtool 这个里面主要用来搭建本地服务和代理设置。
##4. 关于TROUBLESHOOTING
