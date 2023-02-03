# vuetify-money fork version

If you use Vuejs with Vuetify 2.x and you need a component to work with money format, maybe this can help you.

v-text-field: 
R$ 12.345.678,90

v-model: 
12345678.90

## Dependency
- VueJS
- Vuetify 2.x


## Install
```
$ npm install aims-vuetify-money --save

Register component:
1- Create a src/plugins/vuetify-money.js file with the following content:
import Vue from "vue";
import VuetifyMoney from "aims-vuetify-money";
Vue.use(VuetifyMoney);
export default VuetifyMoney;

2- Add file to src/main.js:
import "./plugins/vuetify-money.js";
