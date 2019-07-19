# petsofyoui

This is a place where the Youi team posts pictures of their pets. 

Want to meet our friends? Head to [pets of youi page](http://nickwangyoui.github.io/petsofyoui)


## A little note about this website

It's not very nice looking, but that's okay. It was a project that @philhawksworth (Netlify team) dreamed up as a bit of an easter egg to support the launch of buying custom domains on Netlify. Then, @yourfrienderin begged him to teach her how to create a website in the process. You can make it better! Pull requests welcome <3


## You are a Youier but your pet is missing?

Well that won't do. If your little friend is missing from this site please submit a pull request.

Step 1: [Fork and download this repo](https://help.github.com/en/articles/fork-a-repo)

Step 2: Once you've downloaded the repo, add your pet picture (with name of pet) to the `/images` folder

Step 3: Add the Snippet below to the index.html file
```
<div class="pet">
  <img src="images/{imagename}.jpg" alt="{Your Pet's Name}" />
  <h2>{Your Pet's Name}</h2>
</div>
```

Step 4: 
[Stage your Changes]
`git add .`

[Make a Commit]
`git commit -m 'added PetName'`

[Push your commit]
`git push`

Step 5: [Open a pull request](https://help.github.com/en/articles/creating-a-pull-request-from-a-fork)

Step 6: Wait for someone to approve your request and see it live [here!](http://nickwangyoui.github.io/petsofyoui)

For more information to understand what all this means, here's some [Bonus Reading](https://guides.github.com/introduction/flow/) (Estimated 3-5min)

