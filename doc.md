1. appwrite for backend , .env se containings all ids that conects appwrite to our frontend
   conf folder contains all thoses ids imports value
2. Envirment variable =  abb backend pe data hi save hota hai like id and password which is private use data ku es variable mai dalte taki yahi variable share ho or ess variable ku project ke root mai save kar jase src hai root mai

3. acessing envirment variable =  in env file we make envirment variables ab us vaiale ka acess front mai alag ack mai alag , nextjs mai alag esa hot hai abhi hum vit use kar rahe hai tu us mai different hai  

4. so we make a conf folder beacuse when we import it want ids in string if error error to read sab fail tu hum is conf mai sub dal denge string format mai or export bhi kar denge take koi problem na aye

5. inside appwrite first file is auth.js file will make functions about creating user login logout jab koi nya user aye uske liye and exportings this services , congig.js this file contains fn for database like createpost , deletepost , updatepost , and some fn for uploading file like delete , update , preview simple .
 
 
6. abb reducer ka time tu file bani store ki wha reducer create hua fir export hua store  , fir slice crete(reducer) hui login, logout inside file(authSlice.js)  

7. abb app.jsx mai usestate bani ju loading show karegi default true , dispatch se value ayi fir useeffext bna jisma authservice ka fn call hua user create hua fir data aya tu login warna logout because state update karna is important fir finally chlega ju loading ku false kar dega or fir agar loading false hai tu data screen pe aa jyga simple

7. we make a logout in header beause logout tabhi chlega jab login hoga 

8. forwardRef ju data yha se lekar age componets mai pass karta hai jase login mai username dala abb login ka baad wahi username login ke baad side mai likha hua hai , eski ek select component banaya  ju options ku select karega



9. postcard ek component or crete kiya jismai card  ka preview show honge jab post pe click hoga