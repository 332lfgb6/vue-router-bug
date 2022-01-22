1. ```bash
   git clone https://github.com/332lfgb6/vue-router-bug.git
   ```

2. ```bash
   yarn
   ```

3. ```bash
   yarn prettier
   ```

4. ```bash
   yarn serve
   ```

5. This is the main bug code.

   ```js
   // src\router\index.js
   
   router.beforeResolve((to, from, next) => {
     if (to.path === '/') {
       next('/about')
     } else {
       next()
     }
   })
   ```

6. ![image-20220122180540110](https://user-images.githubusercontent.com/51245335/150634456-befbed20-2271-41b0-b984-eda011b41ae8.png)
    ![image-20220122181150180](https://user-images.githubusercontent.com/51245335/150634468-e002a5f0-c289-4317-8b63-764252e32725.png)




   
