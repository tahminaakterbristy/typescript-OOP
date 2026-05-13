বড় interface থেকে সবসময় সব field দরকার হয় না। তখন আলাদা interface বানালে একই code বারবার লিখতে হয়, যেটা duplication তৈরি করে।


Pick দিয়ে কোনো interface থেকে নির্দিষ্ট কিছু property নিয়ে নতুন type বানানো যায়।
Omit দিয়ে কিছু property বাদ দিয়ে নতুন type তৈরি করা যায়।
 ফলে:
বারবার interface লেখা লাগে না
code duplication কমে
এক জায়গায় change করলে সব জায়গায় reflect হয়

এটাই DRY (Don't Repeat Yourself) principle maintain করে।