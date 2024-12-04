# 大学课程报告Latex模版

这是一个为北京航空航天大学课程报告编写的 LaTeX 模板，旨在提供一个简洁、美观且易于使用的报告格式，帮助学生快速高效地编写符合各类课程报告。本模版**改编自XDU_Report(普通课程报告封面，含老师)模版，同时参考西安电子科技大学的众多前辈改编而来**。

本模版在任课老师布置的结课大作业、小作业无格式要求时方便使用，无痛编译，轻松上手。

## 模版注意事项

- 本模板为自用课程模版，**若任课教师对格式有明确要求，请勿使用此模板 ！！！**

- git clone/download下来以后，文件目录如下所示：

```
BUAA-report-latex
	[文件夹]【请先安装字体，否则报错】Fonts          # 存放字体
	[文件夹] cover                              # 存放校徽校名
	[文件夹] img                                # 存放正文图片
	BUAAreport.sty                             # sty配置文件
	BUAAreport-Demo.pdf						   # 模版最终效果展示pdf
	BUAAreport-Demo.tex						   # tex主文件，编译运行生成pdf
	README.md                                 
	texput.log                                 # LaTeX 编译过程中生成的日志文件
```

- 本模版在本地 `Windows` 环境成功运行，目前暂无overleaf版本（可自行cv） ，本地采用编辑器 `TeXstudio 4.6.3` ，编译方式为 `xelatex`，编码方式为 `UTF-8`
- 运行环境配置完成后，打开`BUAAreport-Demo.tex`文件，可以一键编译运行查看效果。在正式编写个人报告时请**认真按照tex文件开头的若干注释**修改为自己的信息，同时请仔细阅读注释中的注意事项

- 若对本模版封面、图表、代码等样式无法满足需求，请自行修改BUAAreport.sty配置文件，配置文件中基本都有注释，可以无痛化搜索更改有需求的地方
- 其他学校学生若想使用本模版，仅需要修改`cover`文件夹中的校徽和校名即可



##  如何贡献

1. Fork 这个仓库。 
2.  创建一个新的分支 (`git checkout -b feature-branch`)。 
3. 提交你修改的内容 (`git commit -am 'Add new feature'`)。 
4. 推送到你的分支 (`git push origin feature-branch`)。 
5. 创建一个 pull request，描述你的更改，如果发现任何问题或有改进建议，欢迎通过 issue 提交反馈。