## 小畫家 2024/12/03

### 存檔 
```csharp=
private void 儲存檔案ToolStripMenuItem_Click(object sender, EventArgs e)
{
    pictureBox1.Image.Save(@"C:\Users\User\Desktop\1.png", ImageFormat.Png);
}
```
### 顏色
```csharp
Pen p = new Pen(Color.Black, 3);


private void 藍色ToolStripMenuItem_Click(object sender, EventArgs e)
{
    p.Color = Color.Blue;
}
private void 紅色ToolStripMenuItem_Click(object sender, EventArgs e)
{
    p.Color = Color.Red;
}

private void 綠色ToolStripMenuItem_Click(object sender, EventArgs e)
{
    p.Color = Color.Green;
}
```
![image](https://hackmd.io/_uploads/BJCcZNhQyx.png)

### 線條粗細
```csharp
 private void 細ToolStripMenuItem_Click(object sender, EventArgs e)
 {
     p.Width = 3;
 }

 private void 中ToolStripMenuItem_Click(object sender, EventArgs e)
 {
     p.Width = 10;
 }

 private void 粗ToolStripMenuItem_Click(object sender, EventArgs e)
 {
     p.Width = 15;
 }
```
![image](https://hackmd.io/_uploads/H1NbGVhmyx.png)

### 線條樣式
```csharp
 private void 直線ToolStripMenuItem_Click(object sender, EventArgs e)
 {
     p.DashStyle = System.Drawing.Drawing2D.DashStyle.Solid;
 }

 private void 點ToolStripMenuItem_Click(object sender, EventArgs e)
 {
     p.DashStyle = System.Drawing.Drawing2D.DashStyle.Dot;
 }

 private void 長短虛線ToolStripMenuItem_Click(object sender, EventArgs e)
 {
     p.DashStyle = System.Drawing.Drawing2D.DashStyle.DashDot;
 }
private void 長虛線ToolStripMenuItem_Click(object sender, EventArgs e)
{
    p.DashStyle = System.Drawing.Drawing2D.DashStyle.DashDotDot;
}
```
![image](https://hackmd.io/_uploads/S1hdGVnmye.png)
