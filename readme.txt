Random Qur'anic Verse Wordpress 1.5 Plugin (Not tested on 1.2 - tester required)

// v 1.15, added Malay language support.

Steps to install:

1. Download the plug-in (ZIP) and extract.

2. Open your Sidebar.php or any template file and add one of the following:
 <? random_quran() ?>, <? random_quranpic() ?> or <? random_quranpiceng() ?> to where you want the verse to show. To use the 'Malayu' language insert <? random_quranmalay() ?>.

3. To decorate the script just add the <ul> and <li> tags (or any other appropriate tags you want).

4. An example of the code you can insert into the sidebar:

    <li><h2><?php _e(’Random Qur'anic Verse’); ?></h2>
    <ul>
            <? random_quran() ?>
    </ul></il>

After this upload the plug-in to your wp-content/plugins directory and activate it in the admin panel. Your Random Qur'anic Verse should then show up depending on where you have initiated the script.

The advantage of using this plug-in is that you can put the <? random_quran() ?> anywhere on the website! You can even have it after every post.

Special thanks to Kemas Yunus Antonius for the link to the scripts, and http://www.mukmin.info/english/ for the actual scripts.

Usayd Younis

| © Usayd Corp. | www.usayd.com | plugins@usayd.com |