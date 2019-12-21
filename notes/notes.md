## Steps

```
meteor create --release 1.8.1 meteor-template (1.8.2 - 1.8.3 has a bug)
cd meteor-template
meteor npm install --save vue
meteor remove blaze-html-templates
meteor add static-html
meteor add akryum:vue-component

Add content as shown in: https://guide.meteor.com/vue.html

NO_HMR=1 meteor run --port 8085 --settings settings.json

```