# HelloWorld
HelloWorld
	打开Terminal 输入： apt-get install git
告诉Git你的名字，所以你的提交将正确标签 ：                           git config --global user.name “YOUR NAME”
告诉Git将与您的Git提交相关联的电子邮件地址。 您指定的电子邮件应该与您的电子邮件设置中找到的电子邮件相同。 要隐藏您的电子邮件地址，请参阅“https://help.github.com/articles/keeping-your-email-address-private/”。:         																																																								                                                    git config --global user.email "YOUR EMAIL ADDRESS"
通过Git 验证GitHub
		通过HTTPS验证（推荐） 
	git config --global credential.helper cache
	git config --global credential.helper 'cache --timeout=3600'   
通过SSH进行验证
	参考： https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/#platform-linux
