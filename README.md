# EQ for PA speakers
Over quite some time with listening many PA speakers, I've found that many of them are really harsh so I though to myself "why not make this repository in order to make life easier for other PA speaker users and have better sound?"

# Equalizer APO
I use Equalizer APO on a Windows machine to make PA speakers more enjoyable to listen to. Files (.txt) here contain EQ info which you can import and try to see if they sound good and adjust it yourself to fit your needs. You can use this on other equalizers, make sure to apply EQ accordingly to not ruin sound in the end.

If you're using a subwoofer along with the speaker that has EQ (from this repository) on, it's best to set reproducible sub-bass frequencies to -2 (not 0 anymore) so they can be reproduced by the sub with authority. Otherwise, keep the EQ protection as is to protect your woofers.
If you're using a super tweeter on top of the speaker, you might aswell remove 20kHz block. It was put in place as many PA speaker tweeters struggle there and there is not much content anyways that benefits me (likely doesn't benefit you either). Ensure you do the filtering and EQ properly with such addition. This can be fun if you listen to high resolution audio which does have content above 20kHz. This is for me a dangerous territory that has little to no benefit to my ears as I don't listen to such content yet.

If you happen to be able to improve the EQ or have speakers from other brands that you have made EQ with, you may go ahead and fork or branch it which can help everyone improve PA speakers' sound and lifespan in a long run.

# Why -2dB cut?
I've done some heavy testing around slight cuts across the entire spectrum (1Hz-20Khz) for PA speakers and found that cutting 2dB is unnoticable (unless you compare it to the original of course) which gives your amplifier some air to breathe so you are less likely to run into distortion issues. You may go ahead and cut -2dB and ask others (assuming they have listened to the same speakers) if it's any different. The only difference can be noticed is that you turned up the volume with the -2dB cut. This is done by default in all EQs that are here in this repository so you are safe.

If you have a subwoofer or super tweeter by any chance and set their reproducible frequencies to 0, expect it to be louder than your tops. You might aswell do it if you like heavy tuning.

# Notice
This EQ database is still ongoing for best practices to improve your PA equipment lifespan while making them more flat sounding.
