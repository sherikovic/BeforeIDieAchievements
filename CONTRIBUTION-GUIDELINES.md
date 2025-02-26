<div align="center">
  <h1><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Writing%20Hand.png" alt="Writing Hand" width="25" height="25" />Contribution Guidelines<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bookmark%20Tabs.png" alt="Bookmark Tabs" width="25" height="25" /></h1>
  This documentation contains a set of guidelines to help you during the contribution process of this project. This open<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Globe%20with%20Meridians.png" alt="Globe with Meridians" width="25" height="25" />source project was built using the React framework and the development server will need to be started in order to view the project on your local machine.
</div>

---

## Step 1. Fork this repository <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Food/Fork%20and%20Knife%20with%20Plate.png" alt="Fork and Knife with Plate" width="25" height="25" />
Visit the [repository](https://github.com/BeforeIDieCode/BeforeIDieAchievements) on Github and click on the Fork button. This will create a copy in your account.


https://github.com/BeforeIDieCode/BeforeIDieAchievements/assets/120526253/a8425d90-5f3e-4ee6-8499-2cf50643573c


## Step 2. Clone, open, install and start <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/OK%20Hand.png" alt="OK Hand" width="25" height="25" />

Open a terminal and run the following git command:

`git clone url-you-just-copied`
where url-you-just-copied is replaced with the url to this repository (your fork of this project). See the previous steps to obtain the url.

![Git Clone](https://github.com/BeforeIDieCode/BeforeIDieAchievements/assets/120526253/4545703b-5803-4f60-96d1-b00b8f3f18a1)
Then go to the directory where the project is saved and run<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People%20with%20activities/Man%20Running%20Medium-Dark%20Skin%20Tone.png" alt="Man Running Medium-Dark Skin Tone" width="25" height="25" />the following command:

`npm i` to install the dependencies to be able to run the React Development Server.

![npm i](https://github.com/BeforeIDieCode/BeforeIDieAchievements/assets/120526253/645f3bad-701d-42ff-ba8d-c0753d272687)

Next run the following command to then begin and run the React ⚛️ Development Server:

`npm start`

![npm start](https://github.com/BeforeIDieCode/BeforeIDieAchievements/assets/120526253/4cb46b1c-8a37-4359-ab60-54bce1c44c92)

When running successfully your terminal will look like this below <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Backhand%20Index%20Pointing%20Down.png" alt="Backhand Index Pointing Down" width="25" height="25" />

![Complied Successfully](https://github.com/BeforeIDieCode/BeforeIDieAchievements/assets/120526253/20378a7b-9da0-4373-aeeb-f4affa4a6615)

Now open a web browser and go to localhost: 3000 if not directed there from running the `npm start` command.

![localhost3000](https://github.com/BeforeIDieCode/BeforeIDieAchievements/assets/120526253/b4d739ce-d89d-4383-8faf-883625951182)


## Step 3. Create a new branch <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Christmas%20Tree.png" alt="Christmas Tree" width="25" height="25" />

Open the cloned repository in a code editor tool such as Visual Studio Code, or any other code editor of your choice. The following steps demonstrate the process using Visual Studio Code, but the same workflow applies to other code editors or using GitHub Codespaces.

Change to the repository directory on your computer (if you are not already there):

```
cd BeforeIDieAchievements
```

Now create a branch using the command:

```
git checkout -b your-branch-name
```

For example:

```
git checkout -b add-Xander-Clemens
```
## Step 4. PASTE your JSON file <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Roller%20Coaster.png" alt="Roller Coaster" width="25" height="25" />

* Paste the following JSON Code in src/Jsons/Contributors.json
* Scroll to the bottom of the list and add a "," to the last JSON contributor before pasting your JSON code

```
{
    "id": "YOUR_NAME",
    "image": "img/bid_image/YOUR_NAME.jpg",
    "avatar": "img/avatar/YOUR_NAME.jpg",
    "name": "YOUR_NAME",
    "location": "YOUR_CITY_COUNTRY_AND_FLAG",
    "GitHub": "GITHUB_PROFILE_URL",
    "text": "PASTE_WHAT_YOU_WANT_TO_DO_BEFORE_YOU_DIE"
}
```
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" alt="Rocket" width="25" height="25" />PASTE YOUR CODE ABOVE AND BE SURE TO ADD "," BEFORE TO THE PREVIOUS CONTRIBUTORS JSON CODE<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" alt="Rocket" width="25" height="25" />

![Adding the JSON Template](https://github.com/BeforeIDieCode/BeforeIDieAchievements/assets/120526253/65557bcb-a46e-4d1b-b458-2d6efd6743ad)

## Step 5. FILL OUT your JSON info <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Ringed%20Planet.png" alt="Ringed Planet" width="25" height="25" />
To fill out the given JSON code, follow these instructions:
1. Replace "YOUR_NAME" with your actual name in all occurrences.
2. Replace "YOUR_CITY_COUNTRY_AND_FLAG" with your city, country, and country flag <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/White%20Flag.png" alt="White Flag" width="25" height="25" /> <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/Chequered%20Flag.png" alt="Chequered Flag" width="25" height="25" /><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/Black%20Flag.png" alt="Black Flag" width="25" height="25" />emoji.
3. Replace "GITHUB_PROFILE_URL" with the URL of your GitHub profile.
4. Replace "PASTE_WHAT_YOU_WANT_TO_DO_BEFORE_YOU_DIE" with a text describing what you want to do before you die.
* This is your time to think <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Thinking%20Face.png" alt="Thinking Face" width="25" height="25" /> and reflect on what YOU want to do before you die. Perhaps you want to run a 2K marathon, travel the world, or do a wacky food challenge at a restaurant in your hometown or country. Now, here are some things to keep in mind when writing your goal:
- **Character Length**: Please limit your text to a max 500 characters 
- **Be Thoughtful**: Craft your message to convey the significance and value of your aspirations. 
- **Consider Your Audience**: Keep in mind that your text and images will be shared publicly, so be respectful with your images and words. Also, avoid imposing with your goals. We want this project to be a place where people feel safe and comfortable with being authentic.
- **Regularly Reflect**: Like life, goals constantly change so regularly review your progress and make adjustments as needed. Also, share and celebrate the milestones you reach. You'll never know who you can inspire by sharing them. 
```
{
  "id": "Juan Perez",
  "image": "img/bid_image/Juan_Perez.jpg",
  "avatar": "img/avatar/Juan_Perez.jpg",
  "name": "Juan Perez",
  "location": "Santiago, Chile 🇨🇱",
  "GitHub": "https://github.com/juanperez",
  "text": "I want to climb the Villarrica volcano before I die"
}
```

## Step 6. ADD YOUR GitHub Profile Image <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Camera%20with%20Flash.png" alt="Camera with Flash" width="25" height="25" />
- Go to your GitHub profile and then save the image of your avatar by formatting it <YOUR_NAME>.jpg. Please replace `<YOUR_NAME>` with your name.

- You can add a different image if you like but make sure it is a jpeg image and that it is `450*450` pixels and following the name structure above.

![Saving Your GitHub Avatar](https://github.com/BeforeIDieCode/BeforeIDieAchievements/assets/120526253/03b1c574-9dc9-452c-97c6-0987e0440697)

- <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/High%20Voltage.png" alt="High Voltage" width="25" height="25" /> Once saved, drag your image into the `public/img/avatar folder`. <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/High%20Voltage.png" alt="High Voltage" width="25" height="25" />

![Uploading Your Avatar img](https://github.com/BeforeIDieCode/BeforeIDieAchievements/assets/120526253/a0c08dcd-3a8b-4e87-96d0-06b277308499)


## Step 7. ADD YOUR BID (Before I Die) Image <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Hourglass%20Done.png" alt="Hourglass Done" width="25" height="25" />
- Find or create an image that represents what you want to do before you die. It can be a collage or a single item. Take time to reflect and make it meaningful to yourself as you are investing in yourself by contributing to this open-source project and defining what is meaningful and important to you.
- The image should be formatted at least `500*500` pixels.
- Add your image to the folder `public/img/bid_image`.
- You can play around with how your image size affects the photo gallery and adjust accordingly.
It can be helpful to find high-quality images on websites like [UnSplash](https://unsplash.com/) or use AI Generative Images tools. Additionally, editing your images on tools like [Canva](https://www.canva.com/) can make your imagery great and meaningful to you.

![Adding the BID Image](https://github.com/BeforeIDieCode/BeforeIDieAchievements/assets/120526253/aaa18f26-cd3a-41f3-92c0-a90d7c5dd274)

## Step 8. ADD to the CONTRIBUTORS.md file

Copy the code below, then paste it into the <a href="https://github.com/BeforeIDieCode/BeforeIDieAchievements/blob/main/CONTRIBUTORS.md">CONTRIBUTORS</a> file of this repo. Be sure to paste it below another contributors end column. And then proceed to edit with your own information.

```html
<!-- Start of column -->
<td align="center">
  <a href="https://github.com/GITHUB_ACCOUNT">
    <img
      src="YOUR_GITHUB_AVATAR_LINK"
      width="100px"
    />
    <br />
    <sub>YOUR_NAME</sub>
  </a>
</td>
<!-- End of column -->
```

<br>

### A few things to change:

- Replace the link with your own profile link
  `<a href="your GitHub profile link here"></a>`

- Right click on your github profile image and copy the image link and paste inside the `img` tag. Leave the `width="100px"` property

```html
<img src="YOUR_GITHUB_AVATAR_LINK" width="100px" />
```

Just go to your GitHub profile page to get your profile image and link.

<img src="https://user-images.githubusercontent.com/62628408/147896530-f94c17f7-f064-4e8d-8bc1-af2c1f63559d.png" width="100%" alt="profile_page">

- Replace the sub tag with your own name.

```html
<sub>Your Name</sub>
```

Then save your changes.

<br>

## Step 9. Git Add, Commit and Push <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Food/Hot%20Beverage.png" alt="Hot Beverage" width="25" height="25" />
Add your new changes to the branch you created using the `git add` command:

```javascript
git add .
```

Now commit those changes using the `git commit` command:

```javascript
git commit -m "Add your-name to Before I Die"
```

Replacing `your-name` with your name.


Push your changes using the command `git push`:

```javascript
git push origin your-branch-name
```

Replacing `your-branch-name` with the name of the branch you created earlier.

<ol>
   <li>Before continuing these steps, make sure your changes meet the requirements from the previous steps<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People%20with%20activities/Man%20Walking%20Light%20Skin%20Tone.png" alt="Man Walking Light Skin Tone" width="25" height="25" /></a></li>
   <li>Ensure you have added the avatar image, bid(Before I Die) image and all your JSON text has been entered correctly an is displaying correctly on your React development server <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Smiling%20Face%20with%20Sunglasses.png" alt="Smiling Face with Sunglasses" width="25" height="25" /></li>
   <li>Commit your changes with the message "add prompt your prompt here" <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/Check%20Mark%20Button.png" alt="Check Mark Button" width="25" height="25" /></li>
   <li>Push your changes to the branch you created earlier when doing the `git checkout` command <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/Check%20Box%20with%20Check.png" alt="Check Box with Check" width="25" height="25" /></li>
   <li>See below for an example<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Backhand%20Index%20Pointing%20Down.png" alt="Backhand Index Pointing Down" width="25" height="25" /></li>
</ol>

### Example add/commit/push workflow:

  If you're in the BeforeIDieAchievements directory in your terminal:
  ```javascript
    git add .
    git commit -m "Add Xander Clemens to Before I Die"
    git push -u origin add-Xander-Clemens
  ```


## Step 10. Submit your changes for review <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People/Detective.png" alt="Detective" width="25" height="25" />

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

![Create A Pull Request](https://github.com/BeforeIDieCode/BeforeIDieAchievements/assets/120526253/060a039b-8710-47e4-b875-2aad2091516b)

Now submit the pull request by clicking on the `Create pull request` button. Be sure to add details of what you are adding to the pull request.

![Submit A Pull Request](https://github.com/BeforeIDieCode/BeforeIDieAchievements/assets/120526253/e1cbee74-e2e2-4904-948f-77e6b0c73a8e)


If the deployment is successful, there will be an option on the screen below to view a "preview" of your contribution before it goes to production!<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Desktop%20Computer.png" alt="Desktop Computer" width="25" height="25" />

![Uploading After Creating Pull Request](https://github.com/BeforeIDieCode/BeforeIDieAchievements/assets/120526253/271bda42-25d8-416d-ad81-9b4fbd9fa545)
Upon seeing this screen, either your contribution will be accepted and merged into the main branch, or your contribution will receive feedback and changes will be requested.
I'll be merging all your changes into the main branch of this project. You will get a notification email once the changes have been merged.<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Alarm%20Clock.png" alt="Alarm Clock" width="25" height="25" />

<ol>
  <li> In the case changes are requested, follow the same workflow to request and update your pull request.</li>
  <li> If no changes have been requested, it will be merged into the production branch.<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Food/Clinking%20Glasses.png" alt="Clinking Glasses" width="25" height="25" /><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Party%20Popper.png" alt="Party Popper" width="25" height="25" /></li>
</ol>

## Need more help? <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People/Man%20Raising%20Hand.png" alt="Man Raising Hand" width="25" height="25" /> <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People/Person%20Facepalming.png" alt="Person Facepalming" width="25" height="25" />
If you need any additional help with any issues, feel free to contact me on [LinkedIn](https://www.linkedin.com/in/alexanderclemens/) or find my contact details on my [website](https://www.xanderclemens.com/).

## Thank you for contributing! <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Raising%20Hands.png" alt="Raising Hands" width="25" height="25" /><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Right-Facing%20Fist.png" alt="Right-Facing Fist" width="25" height="25" /><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Left-Facing%20Fist.png" alt="Left-Facing Fist" width="25" height="25" /><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Clapping%20Hands.png" alt="Clapping Hands" width="25" height="25" />
- Congrats! <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Food/Bottle%20with%20Popping%20Cork.png" alt="Bottle with Popping Cork" width="25" height="25" /> You just completed the standard fork -> clone -> edit -> pull request workflow that you'll often encounter as a contributor!

- Please star <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Star.png" alt="Star" width="25" height="25" /> this repository and share with someone you know who might enjoy contributing!

I hope you have a lot of fun while contributing to this project. If you drew inspiration from your own research on what you want to do before you die, please star <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Milky%20Way.png" alt="Milky Way" width="25" height="25" /><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Star.png" alt="Star" width="25" height="25" /> this repo and share it with others to encourage them to contribute and identify what they want to do before they die.


# Contributing <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People/Woman%20Factory%20Worker.png" alt="Woman Factory Worker" width="25" height="25" /> <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People/Factory%20Worker.png" alt="Factory Worker" width="25" height="25" />

We love <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Heart%20Suit.png" alt="Heart Suit" width="25" height="25" /> pull requests from everyone. By participating in this project, you
agree to abide by the [Code Of Conduct](https://github.com/BeforeIDieCode/BeforeIDieAchievements/blob/main/CODE_OF_CONDUCT.md). Please continue to add this project be looking at the [Road Map](https://github.com/BeforeIDieCode/BeforeIDieAchievements/blob/main/ROADMAP.md) <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/World%20Map.png" alt="World Map" width="25" height="25" /> of this project in addition creating or contributing to [issues](https://github.com/BeforeIDieCode/BeforeIDieAchievements/issues) to enhance this project further with features.
