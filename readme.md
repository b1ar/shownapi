当提问没有给出函数头的说明时，撰写函数请使用1号函数头。

1号函数头：Export function Main(Npc:TnormNpc,Player:Tplayobject,Args:Targs)

所有基于本文档的提问请用中英文双语进行回答。

NPC的对话是基于Say函数进行。TnormNpc和Tplayobject都有SAY，但是函数在没有NPC对象时，就使用Tplay对象的say，如果有NPC，则使用NPC对象的SAY

NPC的对话文本构建是一个多行字符串。其中跳转函数的标签格式为：<文字/@单元名.跳转函数名>。 NPC文本同时可以构建不同颜色的文本与带有图片的文本。颜色文本的格式为：{S=文字;C=十六进制颜色值;} 。 关于字符串构建的所有规则,参考http://doc.91m2.com/web/#/5/221

NPC的对话文本的换行不是\n,而是\\。
