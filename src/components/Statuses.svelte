<script>
let users = [
    {
      user_img:"https://media.discordapp.net/attachments/1064136472422273054/1067479419159052288/Layona-x_anime_girl_sunshine_forest__orange_sky80s_anime_styler_75853f96-1465-462b-a916-a5b54b85f49b.png",
      user_name:"Layona"
    },{
      user_img:"https://media.discordapp.net/attachments/1064136472422273054/1067479419159052288/Layona-x_anime_girl_sunshine_forest__orange_sky80s_anime_styler_75853f96-1465-462b-a916-a5b54b85f49b.png",
      user_name:"Layona"
    },{
      user_img:"https://media.discordapp.net/attachments/1064136472422273054/1067479419159052288/Layona-x_anime_girl_sunshine_forest__orange_sky80s_anime_styler_75853f96-1465-462b-a916-a5b54b85f49b.png",
      user_name:"Layona"
    },
     {
      user_img:"https://media.discordapp.net/attachments/1064136472422273054/1067479419159052288/Layona-x_anime_girl_sunshine_forest__orange_sky80s_anime_styler_75853f96-1465-462b-a916-a5b54b85f49b.png",
      user_name:"Layona"
     },
       {
      user_img:"https://media.discordapp.net/attachments/1064136472422273054/1067479419159052288/Layona-x_anime_girl_sunshine_forest__orange_sky80s_anime_styler_75853f96-1465-462b-a916-a5b54b85f49b.png",
      user_name:"Layona"
  },
       {
      user_img:"https://media.discordapp.net/attachments/1064136472422273054/1067479419159052288/Layona-x_anime_girl_sunshine_forest__orange_sky80s_anime_styler_75853f96-1465-462b-a916-a5b54b85f49b.png",
      user_name:"Layona"
       },{
       user_img:"https://media.discordapp.net/attachments/1064136472422273054/1067479419159052288/Layona-x_anime_girl_sunshine_forest__orange_sky80s_anime_styler_75853f96-1465-462b-a916-a5b54b85f49b.png",
      user_name:"Layona"
      },{
       user_img:"https://media.discordapp.net/attachments/1064136472422273054/1067479419159052288/Layona-x_anime_girl_sunshine_forest__orange_sky80s_anime_styler_75853f96-1465-462b-a916-a5b54b85f49b.png",
      user_name:"Layona"
       }
  ]
</script>
<div class="overscroll-contain overflow-x-auto overflow-hidden">
<div class="grid grid-flow-col auto-col-auto">
  {#each users as user}
    <div class="block ml-8">
    <img class="w-14 h-14 border border-red-600 rounded-full object-fill" src={user.user_img}>
    <p>{user.user_name}</p>
    </div>
  {/each}
 </div>
</div>