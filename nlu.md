<!--

## intent: <intent_name>
- user_input1
- user_input2
.
.
.
- user_inputN

command to train NLU data : python -m rasa_nlu.train -c nlu_config.yml --data data/nlu.md -o models --fixed_model_name nlu --project current --verbose

-->

## intent: greet
- Hello
- Hey
- Aloha
- Hi
- Howdy
- Hi dear
- Hi Baymax!
- Hi Bay
- What's up?
- 'Sup?
- sup
- heya
- Heyy
- Oye.
- How are you?
- Hello. Wassup?
- Hey ya
- Good morning. 
- Are you there?
- Heya!
- Hola!

## intent: mood_great
- I am doing awesome
- Never been better
- I feel great
- I'm doing great
- Amazing!
- Elated
- I am doing good.
- Bwahaha
- i am good 
- i am great!!
- i am on cloud9
- Great.
- I am great too.
- I'm on the top of the world!!!

## intent: mood_depressed
- I am not doing well
- Been better
- I feel low
- I'm not doing great
- Awful!
- Had a terrible day
- I'm not doing so good.
- i am feeling low cheer me up
- too depressed
- i feel a bit off
- i'm just too bored.
- hey, i am sad!
- I am not having a good day.
- I had a terrible day at [work](location).
- I have been having a bad day.
- I am bored too. Entertain me.
- I am having a horrible day.
- mm..trying to be happy
- just a mild fever!
- Arghhhh!!!
- Well for starters, you could kill that traitor!!!
- Oh god!! Tomorrow I have a competition abd I've not prepared anything.

## intent: request_picture
- I want a picture
- Show me photos

## intent: inform
- A [dog] (group:dog)
- [dog] (group:dog)
- of a [dog] (group:dog)
- [bird] (group:bird)
- show me a [cat]. (group:cat)

## intent: request_joke
- Make me laugh
- Tell me a joke
- Make me smile
- I'm not doing great. Tell me a joke, please.
-  I'm not doing great. Can you make me smile?
- cheer me up
- Send me something funny

## intent: affirm
- Yes, please.
- yes i'll love that
- Yes.
- waiting..
- duh!!

## intent: reject
- no
- i'm just too bored.
- No, that'll just depress me more.
- nah.. 
- Lol! I didnt mean actually kill someone!!!
- Ohk, I dont really like it.
- No, its fine, Ill do that next time.
- No, Thank You!

## intent: repeat
- Another one, please.

## intent: compliment
- Hahaha. You're funny.
- Bwahaha
- that did cheer me
- Thank you.
- Thank you,feels good!
- Thats great! Thank you.
- No that will be all. Thank you!!
- Hey! I like this!

## intent: request_weather
- I'm doing okay. How's the weather?

## intent: request_song
- sing a song

## intent: request_item
- yeah get me a [shawarma](food)!! 
- nah.. just get me a tub of [ice cream](food)
- [missisipi mud](food)
- [Toast](food).
- Can you order [paracetemol](drug)?
- I need to go to the party but it's too far!
- Firstly, play some rap. Order a [pizza](food) and some [fries](food). It's time to PARTYYYY!!!
- I would like to download a [music] clip for my project

## intent: request_suggestions
- I am going out [shopping](suggestion_type). Can you suggest me some places?
- Do you know about any good [party place with pools](suggestion_type:party_spot)?
- I cannot focus. I need to prepare a [song](suggestion_type). Can you help me??
- Could you list them?
- Is there any scifi based [storyboard](suggestion_type) available to work on?

## intent: dogs_song_meme
- Who let the dogs out?

## intent: sw_dad_meme
- You killed my father!

## intent: got_greeting
- Valar Morghulis!

## intent: uri_greeting
- How's the josh?

## intent: misc
- tickle me !!!! 
- Yes. Did you?
- Lol! I didnt mean actually kill someone!!!
- Ok for now you can call my bestfriend. I wanna bitch about that traitor.
- My results just came through!! I still can't believe I cleared VHDL.
- Thanks!! Also I would like to meditate for a while so tell my mom not to disturb me.
- Could you review Dragon Ball Super for me?
- How many episodes?
- Are there more anime reviews available under this genre?


