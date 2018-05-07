# vue.js----delete
Vue.set和Vue.delete属性的简单使用



          var vm=new Vue({
               el:"#app",
              data:{
                     map:[0,1,2,3,4,5,6,7,8,9]
                   },
              });
            //修改
             Vue.set(vm.map,0,777);

             // 删除
              delete vm.map['2'] ;   //这样删除只能删除标签里面的文字
              Vue.delete(vm.map, '3') ;  // 这样删除，标签和文字都会全部删除
          </script>
