## Android 学习记录

---

### Layout 五大布局

参考资料: [官方文档](https://developer.android.com/guide/topics/ui/declaring-layout?hl=zh-CN)

1. 含义
   定义用户界面的视觉结构

2. 声明方式

   - 在 xml 中声明 UI 元素
   - 运行时实例化布局元素

3. 加载 XML 资源
   在`Activity.onCreate()`回调实现布局资源的加载, 如

   ```
   public void onCreate(Bundle savedInstanceState) {
       super.onCreate(savedInstanceState);
       setContentView(R.layout.main_layout);
   }
   ```

   获取 view 对象实例, 如
   `Button myButton = (Button) findViewById(R.id.my_button);`

4. 常见布局

   - 线性布局
   - 相对布局
   - 网页布局
