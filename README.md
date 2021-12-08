# html2html
page copy

应用场景：  
1. 生成 pdf：html2html 生成 htmlstring，调用 [puppeteer](https://zhaoqize.github.io/puppeteer-api-zh_CN/#?product=Puppeteer&version=v11.0.0&show=api-pagepdfoptions) 生成 pdf
2. 复制网页: copy `html2html.js` 代码，直接到浏览器控制台运行，即可下载生成 html 文件
3. 自动骨架屏

待实现  
1. wasm 应用：puppeteer 生成 pdf，目前暂时没有把 nodejs 编译为 wasm 工具。解决思路：提取 puppeteer 内部 c++ 解析 html 和生成 pdf 模块，编译为 wasm 供浏览器调用
2. 浏览器插件：生成 pdf, 复制网页
