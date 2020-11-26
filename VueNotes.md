# Sử dụng axios
1. Cài đặt axios vào project  
$ npm install axios  
2. Import axios vào main.js  
import axios from 'axios'  
3. Khai báo dùng axios trong main.js  
Vue.use(axios)  
4. Import axios vào những nơi muốn dùng  
import axios from 'axios'  
5. Dùng và kiểm tra như ví dụ bên dưới  
     mounted: function(){  
    axios.get('https://api.coindesk.com/v1/bpi/currentprice.json')  
    .then(function(response){  
        //デバッグ用にconsoleに出力  
        console.log(response.data.bpi)  
        this.bpi = response.data.bpi  
    }.bind(this))  
    .catch(function(error){  
        console.log(error)  
    })  
}  

6. Tham khảo tại link bên dưới  
https://qiita.com/yuta-38/items/eb4ccf5b884d12db0a90  

