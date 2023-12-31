# clubfittbuddy
Download the workout card samples to try out [ClubFitt Buddy](http://clubfitt-web-app.s3-website-ap-southeast-1.amazonaws.com/) workout recommendation system. 

## How to use/ How to test the demo
1. Download the [workout card samples here](https://github.com/araii/clubfittbuddy/tree/main). There are 7 samples to test on.
2. **If you are on your mobile phone (Apple),** heres how you can download the jpg to your photo album to test out the site
- Tap on `View code` to see list of workout card samples
- tap on any 'IMG_****.JPG' file
- tap on `...` button on the top right of the **image**  and tap `View`
- when you are shown the image, 'press and hold' the image until a pop up appear - choose `Save to Photos`
3. Once the samples are downloaded, go to [ClubFitt Buddy](http://clubfitt-web-app.s3-website-ap-southeast-1.amazonaws.com/)
4. Upload anyone of the sample workout card.
5. You will be presented with a table showing the results of the scan, make any corrections necessary. (See below for reference or download 'item-meta.csv')
6. Submit the workout log.
7. If you see **ID not found, you will not be able to submit the workout log. You will need to edit the exercise name according to the [workout catalog](https://github.com/araii/clubfittbuddy/blob/main/item-meta.csv) here.
8. Once the submission is successful, you will have the option to "Get Recommendations".
9. The recommendations generated after you click on "Get Recommendations" will be emailed to `tp-ctecproject@maildrop.cc`,
  it is a [publicly accessible mailbox](https://maildrop.cc/inbox/?mailbox=tp-ctecproject). You will be able to see the new exercise recommendation in about 10-15 mins after requesting.

## Please note:
1. Currently there are no user registration for the demo site, so users are mainly 'Richard' (memberId=12) and 'Jonathan' (memberId=3).
2. This site was built to try out AWS AI Cloud-Services such as; **Textract** and **Personalize**.
3. For testing **AWS Personalize** recommendations - 'Jonathan' does mostly upper body workouts, so we would expect the algorithm to pick more lower-body workouts for him.
4. I am sorry that the exercise names in the catalog are not incorporated into the Website UI, but here are the possible names:
   - Bent-over rear-delt fly, Pushups, Reverse ab, Curl over bench, Alternating kettlebell press, Lunge jump, Bench press, Side lateral raise,
   - Drag curl, Squat hold, Bench press, Donkey kicks, Walking lunge,, Curl up biceps, Triceps dip, Upright row and press, Preacher curls,
   - Mountain climber, Weighted sit-up, Barbell bench press, Alternating toe-touch, Dumbbell overhead press, Chest press.
