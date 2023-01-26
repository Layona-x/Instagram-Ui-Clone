<script>
  let posts = [
    {
      post_user:"Layona-x",                      
post_userAvatar:"https://media.discordapp.net/attachments/1064136472422273054/1067479419159052288/Layona-x_anime_girl_sunshine_forest__orange_sky80s_anime_styler_75853f96-1465-462b-a916-a5b54b85f49b.png",
      post_img:"https://media.discordapp.net/attachments/1064136472422273054/1067479419159052288/Layona-x_anime_girl_sunshine_forest__orange_sky80s_anime_styler_75853f96-1465-462b-a916-a5b54b85f49b.png",
      post_liked:"20.000",
      post_desc:"Baaas Lan Baaas",
      
    },{
      post_user:"Layona-x",                      
post_userAvatar:"https://media.discordapp.net/attachments/1064136472422273054/1067479419159052288/Layona-x_anime_girl_sunshine_forest__orange_sky80s_anime_styler_75853f96-1465-462b-a916-a5b54b85f49b.png",
      post_img:"https://media.discordapp.net/attachments/1064136472422273054/1067479419159052288/Layona-x_anime_girl_sunshine_forest__orange_sky80s_anime_styler_75853f96-1465-462b-a916-a5b54b85f49b.png",
      post_liked:"20.000",
      post_desc:"Baaas Lan Baaas",
      
    },{
      post_user:"Layona-x",                      
post_userAvatar:"https://media.discordapp.net/attachments/1064136472422273054/1067479419159052288/Layona-x_anime_girl_sunshine_forest__orange_sky80s_anime_styler_75853f96-1465-462b-a916-a5b54b85f49b.png",
      post_img:"https://media.discordapp.net/attachments/1064136472422273054/1067479419159052288/Layona-x_anime_girl_sunshine_forest__orange_sky80s_anime_styler_75853f96-1465-462b-a916-a5b54b85f49b.png",
      post_liked:"20.000",
      post_desc:"Baaas Lan Baaas",
      
    },{
      post_user:"Layona-x",                      
post_userAvatar:"https://media.discordapp.net/attachments/1064136472422273054/1067479419159052288/Layona-x_anime_girl_sunshine_forest__orange_sky80s_anime_styler_75853f96-1465-462b-a916-a5b54b85f49b.png",
      post_img:"https://media.discordapp.net/attachments/1064136472422273054/1067479419159052288/Layona-x_anime_girl_sunshine_forest__orange_sky80s_anime_styler_75853f96-1465-462b-a916-a5b54b85f49b.png",
      post_liked:"20.000",
      post_desc:"Baaas Lan Baaas",
      
    }]
</script>
{#each posts as post}
<div class="mt-6">
  <div class="flex justify-between">
   <div class="flex">
    <img class="h-8 w-8 ml-2 rounded-full object-fill" src={post.post_userAvatar}>
    <p class="font-bold text-md mt-1 ml-1">{post.post_user}</p>
   </div>
   <div class="">
     <i class="fa-solid fa-ellipsis-vertical mr-4 mt-2"></i>
  </div>
</div>
    <div class="">
      <img class="mt-2 object-fill h-42 w-full" src={post.post_img}>
    </div>
  <div class="block">
    <div class="flex justify-between">
  <div>
    <i class="fa-regular fa-heart text-2xl ml-2 mt-2"></i>
    <i class="fa-regular fa-comment text-2xl ml-4 mt-2"></i>
    <i class="fa-regular fa-paper-plane text-2xl ml-4 mt-2"></i>
    </div>
    <div>
    <i class="fa-regular fa-bookmark mr-2 text-2xl mt-2"></i>
  </div>
  </div>
   <div class="block ml-2">
     <p class="font-bold text-md">{post.post_liked} beğenme</p>
     <div class="flex ">
     <p class="font-bold text-md">{post.post_user}</p>
     <p class="text-md ml-1">{post.post_desc}
    </div>
   </div>
 </div>
</div>
  {/each}