# ant-design-pro-tabs-less
更好看的ant-design-pro-tabs（ant-design-pro v2）

使用方法: 

1. 复制TabPages文件夹到自己的components项目当中
2. scr/layouts/BasicLayout.js中引入该组件
3. 

  ```html
   <Content>
     {children} //注释此行,改为tab组件
     <TabPages {...this.props} homePageKey='/dashboard/home' errorPage={<NoAuth />} />
  </Content>				// homePageKey就是项目首页的url地址

  ```

  
