# WEB5
Додамо в проект пакет mocha за допомогою наступної команди:
npm install mocha --save-dev

Визначимо в папці проекту новий файл package.json наступного змісту:
{
  "name": "testapp",
  "version": "1.0.0",
  "scripts":{
    "test" : "mocha *.test.js"
  },
  "devDependencies": {
    "mocha": "^3.2.0"
  }
}
