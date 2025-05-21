<div>
<table border="1" cellspacing="0" cellpadding="8" align="center">
        <thead>
            <tr>
                <th width="120">類別</th>
                <th width="200">屬性/標籤</th>
                <th width="400">說明</th>
            </tr>
        </thead>
        <tbody>
            <!-- HTML標籤部分 -->
            <tr>
                <td rowspan="4">文本處理標籤</td>
                <td>&lt;h1&gt; - &lt;h6&gt;</td>
                <td>一級標題 - 六級標題</td>
            </tr>
            <tr>
                <td>&lt;br&gt;, &lt;p&gt;</td>
                <td>換行、段落</td>
            </tr>
            <tr>
                <td>&lt;strong&gt;, &lt;em&gt;, &lt;ins&gt;, &lt;del&gt;</td>
                <td>文本加粗、傾斜、底線、刪除線</td>
            </tr>
            <tr>
                <td>&lt;a href="..."&gt;</td>
                <td>超連結（屬性：href，target）</td>
            </tr>
            
            <tr>
                <td rowspan="2">圖片、音視頻標籤</td>
                <td>&lt;img src="..."&gt;</td>
                <td>圖片（路徑：絕對路徑、相對路徑）</td>
            </tr>
            <tr>
                <td>&lt;audio src="..."&gt;, &lt;video src="..."&gt;</td>
                <td>音頻、視頻</td>
            </tr>
            
            <tr>
                <td>佈局標籤</td>
                <td>&lt;div&gt;, &lt;span&gt;</td>
                <td>沒有語義的佈局標籤，配合CSS實現頁面佈局</td>
            </tr>
            
            <tr>
                <td rowspan="3">表格標籤</td>
                <td>&lt;table&gt;, &lt;thead&gt;, &lt;tbody&gt;</td>
                <td>表格、表頭、表格主體</td>
            </tr>
            <tr>
                <td>&lt;tr&gt; / &lt;th&gt;, &lt;td&gt;</td>
                <td>行 / 儲存格</td>
            </tr>
            <tr>
                <td>&lt;form&gt;</td>
                <td>定義表單（屬性：action，method）</td>
            </tr>
            
            <tr>
                <td rowspan="2">表單標籤</td>
                <td>&lt;input type="text/button"&gt;</td>
                <td>表單項（文字輸入框、按鈕...）</td>
            </tr>
            <tr>
                <td>&lt;select&gt; / &lt;option&gt;</td>
                <td>表單項（下拉清單/選項）</td>
            </tr>

            <!-- CSS盒子模型部分 -->
            <tr>
                <td rowspan="6">盒子模型</td>
                <td>width, height</td>
                <td>高度、寬度</td>
            </tr>
            <tr>
                <td>box-sizing</td>
                <td>高度和寬度的計算方式；content-box, border-box</td>
            </tr>
            <tr>
                <td>padding</td>
                <td>內邊距（上、右、下、左；上下、左右）</td>
            </tr>
            <tr>
                <td>border</td>
                <td>邊框</td>
            </tr>
            <tr>
                <td>margin</td>
                <td>外邊距（上、右、下、左；上下、左右）</td>
            </tr>
            <tr>
                <td><b>作用</b></td>
                <td>控制元素尺寸、內邊距、邊框、外邊距，從而控制頁面的佈局展示</td>
            </tr>

            <!-- Flex彈性佈局部分 -->
            <tr>
                <td rowspan="3">flex彈性佈局</td>
                <td>display</td>
                <td>flex：使用flex佈局</td>
            </tr>
            <tr>
                <td>flex-direction</td>
                <td>設置主軸方向（row：x軸，水平方向；column：y軸，垂直方向）</td>
            </tr>
            <tr>
                <td>justify-content</td>
                <td>子元素在主軸上的對齊方式</td>
            </tr>
        </tbody>
    </table>
</div>
