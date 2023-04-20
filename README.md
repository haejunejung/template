# **Github Settings**

📦.github  
┣ 📂ISSUE_TEMPLATE  
┃ ┣ 📜bug.yml  
┃ ┣ 📜feature.yml  
┃ ┣ 📜help.yml  
┃ ┗ 📜question.yml  
┣ 📜.gitmessage.txt  
┗ 📜pull_request_template.md

추가적으로, issue template 각자에는 맞춰진 label들이 있는데 이것을 추가해주면 됩니다.

## **commit message**

- global로 설정하고 싶을 때

```bash
git config --global commit.template .gitmessage.txt
```

- repo마다 설정을 하고 싶을 때

```bash
git config commit.template .gitmessage.txt
```

- 사용 방법

```bash
기존 : git commit -m "message 내용"

변경 : git commit
```

이후 commit template의 내용이 뜨는데, 컨벤션에 맞도록 작성하면 됩니다.

<hr>
나중에 협업이 필요할 때 사용하기 위해 작성한 탬플릿입니다.

필요하다면, 언제든 사용하세요!  
추가적으로, 궁금한 점이 있으시거나 도움이 필요하시다면 ISSUE를 써보세요!
