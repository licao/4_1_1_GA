# 4.1.1.GA
### 修改ti的sdk 让label支持行间距

属性：ATTRIBUTE_LINE_SPACING

用法例子：

	var attr = Titanium.UI.createAttributedString({
		text: text,
		attributes: [{
			type: Titanium.UI.ATTRIBUTE_LINE_SPACING,
			value: "30",
			range: [0, text.length]
		}]
	});
	
	type: Titanium.UI.ATTRIBUTE_LINE_SPACING
	value: 30 or "30" 数字
	range: [起始位置，长度]