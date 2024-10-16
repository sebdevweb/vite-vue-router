# Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

Learn more about IDE Support for Vue in the [Vue Docs Scaling up Guide](https://vuejs.org/guide/scaling-up/tooling.html#ide-support).


## STEPS ##
1. modifiy vite.config.js (add fileURLToPath)
2. add jsconfig.json
3. clean App.vue
4. install vue-router@4 --save
5. create instance on main.js
6. define route of Home component in main.js
7. create Home.vue component
8. import Home component in main.js
9. define route of About component in main.js
10. create About.vue component
11. import About component in main.js
12. add <router-view> in App.vue
13. add <router-link> in App.vue
14. create <a> link to demonstrate the difference between router-link & a link
15. add router/index.js => add routes from main.js
16. add export in router/index.js
17. add import router from router/index.js to main.js
18. define routes in const

--

IMPORT ASSETS

19. add new sources files in project (/images => /public, data.json => /src, main.css => /public)
20. add main.css to index.html
21. remove style form App.vue
22. remove Homepage component
23. wrap <router-view> in App.vue
24. add new component Brazil.vue
25. rename /components to /views
26. add others components (Jamaica, Panama, Hawaii)
27. import datas in App.vue

-- 

LAZY LOADING ROUTES

28. refactoring components import in const routes (router/index.js) to separate page files
29. add navigation component
30. add linkActiveClass into index.js and add css

--

DYNAMIC ROUTES

31. add new route in router/index.js
32. import dataSource in DestinationShow.vue
33. add dataSource from json into DestinationShow page
34. named routes
35. clean up

-- 

REACTING TO PARAM CHANGES

36. See the problems with dummy API
37. route props

--

EXPERIENCE CARDS
38. add section experiences
39. add props experience in ExperienceCard.vue
40. add ExperienceShow.vue
41. add children route to /destination/ :id/:slug
42. add go back component