<template>
  <div class="container" id="app">
    <div class="row d-flex mb-3 align-items-center">
      <div class="col-sm-4">
        <img class="img-fluid d-block" :src="image" :alt="name">
      </div>
      <div class="col">
        <h3 class="text-info">{{ name }}</h3>
        <p class="my-2">{{ description }}</p>
        <div class="mt-4 h5 float-left">${{price}}</div>
      </div>
    </div>
  </div>
</template>



// <script>
// export default {
//   data() {
//     return {
//       persons: [
//         {
//           name: "Nike React Presto",
//           description:
//             "Taking a cue from the early 2000s original, the Nike React Presto plays up its past with a cast of characters for your feet. A stretchy sleeve and foam midsole deliver a relaxed sensation for all-day comfort, while numerous lacing options let you customize your look.",
//           price: 99,
//           image:
//             "https://c.static-nike.com/a/images/f_auto/q_auto/t_PDP_864_v1/o17uvxaiwzuaxmmqp5qx/react-presto-womens-shoe-ZQLnCD.jpg"
//         }
//       ]
//     };
//   }
// };
//
</script>

<script>
export default {
  name: "HelloWorld",
  data() {
    return (
      {
        name: "Nike React Presto",
        description:
          "Taking a cue from the early 2000s original, the Nike React Presto plays up its past with a cast of characters for your feet. A stretchy sleeve and foam midsole deliver a relaxed sensation for all-day comfort, while numerous lacing options let you customize your look.",
        price: 120,
        image:
          "https://c.static-nike.com/a/images/f_auto/q_auto/t_PDP_864_v1/o17uvxaiwzuaxmmqp5qx/react-presto-womens-shoe-ZQLnCD.jpg"
      },
      {
        name: "Nike React Presto",
        description:
          "Taking a cue from the early 2000s original, the Nike React Presto plays up its past with a cast of characters for your feet. A stretchy sleeve and foam midsole deliver a relaxed sensation for all-day comfort, while numerous lacing options let you customize your look.",
        price: 100,
        image:
          "https://c.static-nike.com/a/images/f_auto/q_auto/t_PDP_864_v1/o17uvxaiwzuaxmmqp5qx/react-presto-womens-shoe-ZQLnCD.jpg"
      },
      {
        name: "Nike React Presto",
        description:
          "Taking a cue from the early 2000s original, the Nike React Presto plays up its past with a cast of characters for your feet. A stretchy sleeve and foam midsole deliver a relaxed sensation for all-day comfort, while numerous lacing options let you customize your look.",
        price: 60,
        image:
          "https://c.static-nike.com/a/images/f_auto/q_auto/t_PDP_864_v1/o17uvxaiwzuaxmmqp5qx/react-presto-womens-shoe-ZQLnCD.jpg"
      }
    );
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
