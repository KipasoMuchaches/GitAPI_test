# GitAPI_test
____
## Описание
____
Этот проект содержит скрипт на Python, который выполняет следующие действия с помощью GitHub API:

* Создание нового репозитория
* Проверка его наличия в списке репозиториев
* Удаление репозитория
**Установка**
  ____
  ##1. Клонируйте репозиторий
  '''
  git clone https://github.com/hudhuud/Github_Api_test.git
  cd github-api-test
  '''
  ##2. Установите зависимости
  '''
  pip install -r requirements.txt
  '''
  ##3. Создайте файл .env в корне проекта и добавьте ваши данные
  '''
  GITHUB_TOKEN=your_github_token_here
  GITHUB_USERNAME=your_github_username_here
  REPO_NAME=repo_name_to_create
  '''
  ##4. Запустите скрипт
  '''
  python test_api.py
  '''
  
  
  
