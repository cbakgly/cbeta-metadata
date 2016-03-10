# cbeta.xml: CBETA 部類目錄

tree 元素表示整個樹狀目錄，id 屬性是該目錄的 ID。

node 元素表示樹狀目錄中的一個節點

work 屬性：典籍經號（經號）

跨冊的典籍只記錄一個典籍編號 (JB277 跨 J32~33)

	<node work="JB277"/>

該節點下只有一部典籍

	<node name="T1957 南北朝著作" work="T1957"/>

典籍編號 起迄

	<node work="T1745..T1748"/>

指出該節點下 典籍編號 起迄

	<node name="T1749-54 觀無量壽經疏 T37" work="T1749..T1754"/>

juan 屬性：指到某部典籍的部份卷數

	<node name="T0310(5) 無量壽如來會 2 菩提流志" work="T0310" juan="17..18"/>

file 屬性：指出對應典籍的 XML 檔主檔名

	<node work="T0220" file="T05n0220a" juan="1..200"/>

# 各藏 部別目錄

* cat-t.xml: 大正藏 部別目錄
* cat-x.xml: 卍續藏 部別目錄

# 各藏 冊別目錄

* vol-t.xml: 大正藏 冊別目錄
* vol-x.xml: 卍續藏 冊別目錄