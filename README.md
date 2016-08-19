SocialShare
===========
jQuery plugin


SocialShare is ideal choice for start to create custom social share buttons and share counters.

### Simple example for generate share links:


```javascript
$('.share').ShareLink({
    title: 'My great post', // title for share message
    text: 'text of my great post', // text for share message
    image: 'http://my-site-url.com/images/funny-cats.png', // optional image for share message (not for all networks)
    url: 'http://my-site-url.com/my-article.html', // link on shared page
    class_prefix: 's_', // optional class prefix for share elements (buttons or links or everything), default: 's_'
    width: 640, // optional popup initial width
    height: 480 // optional popup initial height
})
```

### Simple example for create share counters:


```javascript
$('.counter').ShareCounter({
    url: 'http://my-site-url.com/my-article.html', // url for which you want show like counter
    class_prefix: 'c_', // optional class prefix for counter elements, default: 'c_'
    display_counter_from: 0, // optional to set when counter is display, default: 0
    increment: false // Optional. If this option is true you can summarize counters from different sources just using multiple classes for one container.
})
```

#### [Example in action](https://raw.githack.com/AyumuKasuga/SocialShare/master/example.html)


### Supported social networks


#### for now supported networks for like counters:

<table>
    <tr>
        <th>network</th>
        <th>link</th>
        <th>class with default prefix (c_)</th>
    </tr>
    <tr>
        <td>Vkontakte</td>
        <td>https://vk.com/</td>
        <td>c_vk</td>
    </tr>
    <tr>
        <td>Мой Мир</td>
        <td>http://my.mail.ru/</td>
        <td>c_myworld</td>
    </tr>
    <tr>
        <td>Linkedin</td>
        <td>http://www.linkedin.com/</td>
        <td>c_linkedin</td>
    </tr>
    <tr>
        <td>Одноклассники</td>
        <td>http://odnoklassniki.ru/</td>
        <td>c_odnoklassniki</td>
    </tr>
    <tr>
        <td>Pinterest</td>
        <td>http://www.pinterest.com/</td>
        <td>c_pinterest</td>
    </tr>
    <tr>
        <td>Google +</td>
        <td>https://plus.google.com/</td>
        <td>c_plus</td>
    </tr>
</table>

#### for generate share link address:

<table>
    <tr>
        <th>network</th>
        <th>link</th>
        <th>class with default prefix (s_)</th>
    </tr>
    <tr>
        <td>Twitter</td>
        <td>https://twitter.com/</td>
        <td>s_twitter</td>
    </tr>
    <tr>
        <td>Facebook</td>
        <td>https://www.facebook.com/</td>
        <td>s_facebook</td>
    </tr>
    <tr>
        <td>Vkontakte</td>
        <td>https://vk.com/</td>
        <td>s_vk</td>
    </tr>
    <tr>
        <td>Мой Мир</td>
        <td>http://my.mail.ru/</td>
        <td>s_myworld</td>
    </tr>
    <tr>
        <td>Linkedin</td>
        <td>http://www.linkedin.com/</td>
        <td>s_linkedin</td>
    </tr>
    <tr>
        <td>Одноклассники</td>
        <td>http://odnoklassniki.ru/</td>
        <td>s_odnoklassniki</td>
    </tr>
    <tr>
        <td>Pinterest</td>
        <td>http://www.pinterest.com/</td>
        <td>s_pinterest</td>
    </tr>
    <tr>
        <td>Tumblr</td>
        <td>https://www.tumblr.com/</td>
        <td>s_tumblr</td>
    </tr>
    <tr>
        <td>Blogger</td>
        <td>https://www.blogger.com</td>
        <td>s_blogger</td>
    </tr>
    <tr>
        <td>Delicious</td>
        <td>https://delicious.com/</td>
        <td>s_delicious</td>
    </tr>
    <tr>
        <td>Google +</td>
        <td>https://plus.google.com/</td>
        <td>s_plus</td>
    </tr>
    <tr>
        <td>Digg</td>
        <td>http://digg.com/</td>
        <td>s_digg</td>
    </tr>
    <tr>
        <td>Reddit</td>
        <td>http://www.reddit.com/</td>
        <td>s_reddit</td>
    </tr>
    <tr>
        <td>Stumbleupon</td>
        <td>http://www.stumbleupon.com/</td>
        <td>s_stumbleupon</td>
    </tr>
    <tr>
        <td>Pocket</td>
        <td>http://getpocket.com/</td>
        <td>s_pocket</td>
    </tr>
    <tr>
        <td>Chiq</td>
        <td>http://www.chiq.com/</td>
        <td>s_chiq</td>
    </tr>
    <tr>
        <td>Qrifier</td>
        <td>http://www.qrifier.com/</td>
        <td>s_qrifier</td>
    </tr>
    <tr>
        <td>Qrsrc</td>
        <td>http://www.qrsrc.com/</td>
        <td>s_qrsrc</td>
    </tr>
    <tr>
        <td>Qzone</td>
        <td>http://qzone.qq.com/</td>
        <td>s_s_qzone</td>
    </tr>
    <tr>
        <td>Tulinq</td>
        <td>http://www.tulinq.com/</td>
        <td>s_tulinq</td>
    </tr>
    <tr>
        <td>Mister Wong</td>
        <td>http://www.mister-wong.com/</td>
        <td>s_misterwong</td>
    </tr>
    <tr>
        <td>100zakladok</td>
        <td>http://www.100zakladok.ru/</td>
        <td>s_sto_zakladok</td>
    </tr>
    <tr>
        <td>2linkme</td>
        <td>http://www.2linkme.com/</td>
        <td>s_two_linkme</td>
    </tr>
    <tr>
        <td>Adifni</td>
        <td>http://www.adifni.com/</td>
        <td>s_adifni</td>
    </tr>
    <tr>
        <td>Amazonwishlist</td>
        <td>http://www.amazon.com/</td>
        <td>s_amazonwishlist</td>
    </tr>
    <tr>
        <td>Amenme</td>
        <td>http://www.amenme.com/</td>
        <td>s_amenme</td>
    </tr>
    <tr>
        <td>Aim</td>
        <td>http://lifestream.aol.com/</td>
        <td>s_aim</td>
    </tr>
    <tr>
        <td>Aolmail</td>
        <td>http://webmail.aol.com/</td>
        <td>s_aolmail</td>
    </tr>
    <tr>
        <td>Arto</td>
        <td>http://www.arto.com/</td>
        <td>s_arto</td>
    </tr>
    <tr>
        <td>Baidu</td>
        <td>http://baidu.com/</td>
        <td>s_baidu</td>
    </tr>
    <tr>
        <td>Bitly</td>
        <td>https://bitly.com/</td>
        <td>s_bitly</td>
    </tr>
    <tr>
        <td>Bizsugar</td>
        <td>http://www.bizsugar.com/</td>
        <td>s_bizsugar</td>
    </tr>
    <tr>
        <td>Blinklist</td>
        <td>http://www.blinklist.com/</td>
        <td>s_blinklist</td>
    </tr>
    <tr>
        <td>Blip</td>
        <td>http://blip.pl/</td>
        <td>s_blip</td>
    </tr>
    <tr>
        <td>Blogmarks</td>
        <td>http://blogmarks.net/</td>
        <td>s_blogmarks</td>
    </tr>
    <tr>
        <td>Blurpalicious</td>
        <td>http://www.blurpalicious.com/</td>
        <td>s_blurpalicious</td>
    </tr>
    <tr>
        <td>Bobrdobr</td>
        <td>http://bobrdobr.ru/</td>
        <td>s_bobrdobr</td>
    </tr>
    <tr>
        <td>Bonzobox</td>
        <td>http://bonzobox.com/</td>
        <td>s_bonzobox</td>
    </tr>
    <tr>
        <td>Bookmerkende</td>
        <td>http://www.bookmerken.de/</td>
        <td>s_bookmerkende</td>
    </tr>
    <tr>
        <td>Box</td>
        <td>https://www.box.net/</td>
        <td>s_box</td>
    </tr>
    <tr>
        <td>Bryderi</td>
        <td>http://bryderi.se/</td>
        <td>s_bryderi</td>
    </tr>
    <tr>
        <td>Buddymarks</td>
        <td>http://buddymarks.com/</td>
        <td>s_buddymarks</td>
    </tr>
    <tr>
        <td>Camyoo</td>
        <td>http://www.camyoo.com/</td>
        <td>s_camyoo</td>
    </tr>
    <tr>
        <td>Care2</td>
        <td>http://www.care2.com/</td>
        <td>s_care2</td>
    </tr>
    <tr>
        <td>Citeulike</td>
        <td>http://www.citeulike.org/</td>
        <td>s_citeulike</td>
    </tr>
    <tr>
        <td>Classicalplace</td>
        <td>http://www.classicalplace.com/</td>
        <td>s_classicalplace</td>
    </tr>
    <tr>
        <td>Cosmiq</td>
        <td>http://www.cosmiq.de/</td>
        <td>s_cosmiq</td>
    </tr>
    <tr>
        <td>Diggita</td>
        <td>http://www.diggita.it/</td>
        <td>s_diggita</td>
    </tr>
    <tr>
        <td>Diigo</td>
        <td>http://www.diigo.com/</td>
        <td>s_diigo</td>
    </tr>
    <tr>
        <td>Domelhor</td>
        <td>http://domelhor.net/</td>
        <td>s_domelhor</td>
    </tr>
    <tr>
        <td>Dotnetshoutout</td>
        <td>http://dotnetshoutout.com/</td>
        <td>s_dotnetshoutout</td>
    </tr>
    <tr>
        <td>Douban</td>
        <td>http://www.douban.com/</td>
        <td>s_douban</td>
    </tr>
    <tr>
        <td>Dropjack</td>
        <td>http://www.dropjack.com/</td>
        <td>s_dropjack</td>
    </tr>
    <tr>
        <td>Edelight</td>
        <td>http://www.edelight.de/</td>
        <td>s_edelight</td>
    </tr>
    <tr>
        <td>Ekudos</td>
        <td>http://www.ekudos.nl/</td>
        <td>s_ekudos</td>
    </tr>
    <tr>
        <td>Elefantapl</td>
        <td>http://elefanta.pl/</td>
        <td>s_elefantapl</td>
    </tr>
    <tr>
        <td>Embarkons</td>
        <td>http://www.embarkons.com/</td>
        <td>s_embarkons</td>
    </tr>
    <tr>
        <td>Evernote</td>
        <td>http://www.evernote.com/</td>
        <td>s_evernote</td>
    </tr>
    <tr>
        <td>Extraplay</td>
        <td>http://www.extraplay.com/</td>
        <td>s_extraplay</td>
    </tr>
    <tr>
        <td>Ezyspot</td>
        <td>http://www.ezyspot.com/</td>
        <td>s_ezyspot</td>
    </tr>
    <tr>
        <td>Fabulously40</td>
        <td>http://fabulously40.com/</td>
        <td>s_fabulously40</td>
    </tr>
    <tr>
        <td>Informazione</td>
        <td>http://informazione.it/</td>
        <td>s_informazione</td>
    </tr>
    <tr>
        <td>Fark</td>
        <td>http://www.fark.com/</td>
        <td>s_fark</td>
    </tr>
    <tr>
        <td>Farkinda</td>
        <td>http://www.farkinda.com/</td>
        <td>s_farkinda</td>
    </tr>
    <tr>
        <td>Favable</td>
        <td>http://www.favable.com/</td>
        <td>s_favable</td>
    </tr>
    <tr>
        <td>Favlogde</td>
        <td>http://www.favlog.de/</td>
        <td>s_favlogde</td>
    </tr>
    <tr>
        <td>Flaker</td>
        <td>http://flaker.pl/</td>
        <td>s_flaker</td>
    </tr>
    <tr>
        <td>Folkd</td>
        <td>http://www.folkd.com/</td>
        <td>s_folkd</td>
    </tr>
    <tr>
        <td>Fresqui</td>
        <td>http://fresqui.com/</td>
        <td>s_fresqui</td>
    </tr>
    <tr>
        <td>Friendfeed</td>
        <td>http://friendfeed.com/</td>
        <td>s_friendfeed</td>
    </tr>
    <tr>
        <td>Funp</td>
        <td>http://funp.com/</td>
        <td>s_funp</td>
    </tr>
    <tr>
        <td>Fwisp</td>
        <td>http://fwisp.com/</td>
        <td>s_fwisp</td>
    </tr>
    <tr>
        <td>Gmail</td>
        <td>http://mail.google.com/</td>
        <td>s_gmail</td>
    </tr>
    <tr>
        <td>Goodnoows</td>
        <td>http://goodnoows.com/</td>
        <td>s_goodnoows</td>
    </tr>
    <tr>
        <td>Google</td>
        <td>http://www.google.com/</td>
        <td>s_google</td>
    </tr>
    <tr>
        <td>Googletranslate</td>
        <td>http://translate.google.com/</td>
        <td>s_googletranslate</td>
    </tr>
    <tr>
        <td>Greaterdebater</td>
        <td>http://greaterdebater.com/</td>
        <td>s_greaterdebater</td>
    </tr>
    <tr>
        <td>Hackernews</td>
        <td>http://news.ycombinator.com/</td>
        <td>s_hackernews</td>
    </tr>
    <tr>
        <td>Hatena</td>
        <td>http://b.hatena.ne.jp/</td>
        <td>s_hatena</td>
    </tr>
    <tr>
        <td>Hedgehogs</td>
        <td>http://www.hedgehogs.net/</td>
        <td>s_hedgehogs</td>
    </tr>
    <tr>
        <td>Hotmail</td>
        <td>http://www.hotmail.msn.com/</td>
        <td>s_hotmail</td>
    </tr>
    <tr>
        <td>W3validator</td>
        <td>http://validator.w3.org/</td>
        <td>s_w3validator</td>
    </tr>
    <tr>
        <td>Ihavegot</td>
        <td>http://www.ihavegot.com/</td>
        <td>s_ihavegot</td>
    </tr>
    <tr>
        <td>Instapaper</td>
        <td>http://www.instapaper.com/</td>
        <td>s_instapaper</td>
    </tr>
    <tr>
        <td>Isociety</td>
        <td>http://isociety.be/</td>
        <td>s_isociety</td>
    </tr>
    <tr>
        <td>Iwiw</td>
        <td>http://iwiw.hu/</td>
        <td>s_iwiw</td>
    </tr>
    <tr>
        <td>Jamespot</td>
        <td>http://www.jamespot.com/</td>
        <td>s_jamespot</td>
    </tr>
    <tr>
        <td>Jumptags</td>
        <td>http://www.jumptags.com/</td>
        <td>s_jumptags</td>
    </tr>
    <tr>
        <td>Kaboodle</td>
        <td>http://www.kaboodle.com/</td>
        <td>s_kaboodle</td>
    </tr>
    <tr>
        <td>Kaevur</td>
        <td>http://kaevur.com/</td>
        <td>s_kaevur</td>
    </tr>
    <tr>
        <td>Kledy</td>
        <td>http://www.kledy.de/</td>
        <td>s_kledy</td>
    </tr>
    <tr>
        <td>Librerio</td>
        <td>http://www.librerio.com/</td>
        <td>s_librerio</td>
    </tr>
    <tr>
        <td>Linkuj</td>
        <td>http://linkuj.cz/</td>
        <td>s_linkuj</td>
    </tr>
    <tr>
        <td>Livejournal</td>
        <td>http://www.livejournal.com/</td>
        <td>s_livejournal</td>
    </tr>
    <tr>
        <td>Logger24</td>
        <td>http://logger24.com/</td>
        <td>s_logger24</td>
    </tr>
    <tr>
        <td>Mashbord</td>
        <td>http://mashbord.com/</td>
        <td>s_mashbord</td>
    </tr>
    <tr>
        <td>Meinvz</td>
        <td>http://www.meinvz.net/</td>
        <td>s_meinvz</td>
    </tr>
    <tr>
        <td>Mekusharim</td>
        <td>http://mekusharim.walla.co.il/</td>
        <td>s_mekusharim</td>
    </tr>
    <tr>
        <td>Memori</td>
        <td>http://memori.ru/</td>
        <td>s_memori</td>
    </tr>
    <tr>
        <td>Meneame</td>
        <td>http://www.meneame.net/</td>
        <td>s_meneame</td>
    </tr>
    <tr>
        <td>Mixi</td>
        <td>http://mixi.jp/</td>
        <td>s_mixi</td>
    </tr>
    <tr>
        <td>Moemesto</td>
        <td>http://moemesto.ru/</td>
        <td>s_moemesto</td>
    </tr>
    <tr>
        <td>Myspace</td>
        <td>http://www.myspace.com/</td>
        <td>s_myspace</td>
    </tr>
    <tr>
        <td>N4g</td>
        <td>http://www.n4g.com/</td>
        <td>s_n4g</td>
    </tr>
    <tr>
        <td>Netlog</td>
        <td>http://www.netlog.com/</td>
        <td>s_netlog</td>
    </tr>
    <tr>
        <td>Netvouz</td>
        <td>http://netvouz.com/</td>
        <td>s_netvouz</td>
    </tr>
    <tr>
        <td>Newstrust</td>
        <td>http://newstrust.net/</td>
        <td>s_newstrust</td>
    </tr>
    <tr>
        <td>Newsvine</td>
        <td>http://www.newsvine.com/</td>
        <td>s_newsvine</td>
    </tr>
    <tr>
        <td>Nujij</td>
        <td>http://nujij.nl/</td>
        <td>s_nujij</td>
    </tr>
    <tr>
        <td>Oknotizie</td>
        <td>http://oknotizie.virgilio.it/</td>
        <td>s_oknotizie</td>
    </tr>
    <tr>
        <td>Oyyla</td>
        <td>http://www.oyyla.com/</td>
        <td>s_oyyla</td>
    </tr>
    <tr>
        <td>Pdfonline</td>
        <td>http://savepageaspdf.pdfonline.com/</td>
        <td>s_pdfonline</td>
    </tr>
    <tr>
        <td>Pdfmyurl</td>
        <td>http://pdfmyurl.com/</td>
        <td>s_pdfmyurl</td>
    </tr>
    <tr>
        <td>Phonefavs</td>
        <td>http://phonefavs.com/</td>
        <td>s_phonefavs</td>
    </tr>
    <tr>
        <td>Plaxo</td>
        <td>http://www.plaxo.com/</td>
        <td>s_plaxo</td>
    </tr>
    <tr>
        <td>Plurk</td>
        <td>http://www.plurk.com/</td>
        <td>s_plurk</td>
    </tr>
    <tr>
        <td>Posteezy</td>
        <td>http://posteezy.com/</td>
        <td>s_posteezy</td>
    </tr>
    <tr>
        <td>Pusha</td>
        <td>http://www.pusha.se/</td>
        <td>s_pusha</td>
    </tr>
    <tr>
        <td>Rediff</td>
        <td>http://share.rediff.com/</td>
        <td>s_rediff</td>
    </tr>
    <tr>
        <td>Redkum</td>
        <td>http://www.redkum.com/</td>
        <td>s_redkum</td>
    </tr>
    <tr>
        <td>Scoopat</td>
        <td>http://scoop.at/</td>
        <td>s_scoopat</td>
    </tr>
    <tr>
        <td>Sekoman</td>
        <td>http://sekoman.lv/</td>
        <td>s_sekoman</td>
    </tr>
    <tr>
        <td>Shaveh</td>
        <td>http://shaveh.co.il/</td>
        <td>s_shaveh</td>
    </tr>
    <tr>
        <td>Shetoldme</td>
        <td>http://shetoldme.com/</td>
        <td>s_shetoldme</td>
    </tr>
    <tr>
        <td>Sinaweibo</td>
        <td>http://v.t.sina.com.cn/</td>
        <td>s_sinaweibo</td>
    </tr>
    <tr>
        <td>Sodahead</td>
        <td>http://www.sodahead.com/</td>
        <td>s_sodahead</td>
    </tr>
    <tr>
        <td>Sonico</td>
        <td>http://www.sonico.com/</td>
        <td>s_sonico</td>
    </tr>
    <tr>
        <td>Springpad</td>
        <td>http://springpadit.com/</td>
        <td>s_springpad</td>
    </tr>
    <tr>
        <td>Startaid</td>
        <td>http://www.startaid.com/</td>
        <td>s_startaid</td>
    </tr>
    <tr>
        <td>Startlap</td>
        <td>http://www.startlap.hu/</td>
        <td>s_startlap</td>
    </tr>
    <tr>
        <td>Studivz</td>
        <td>http://www.studivz.net/</td>
        <td>s_studivz</td>
    </tr>
    <tr>
        <td>Stuffpit</td>
        <td>http://www.stuffpit.com/</td>
        <td>s_stuffpit</td>
    </tr>
    <tr>
        <td>Stumpedia</td>
        <td>http://www.stumpedia.com/</td>
        <td>s_stumpedia</td>
    </tr>
    <tr>
        <td>Svejo</td>
        <td>http://svejo.net/</td>
        <td>s_svejo</td>
    </tr>
    <tr>
        <td>Symbaloo</td>
        <td>http://www.symbaloo.com/</td>
        <td>s_symbaloo</td>
    </tr>
    <tr>
        <td>Thewebblend</td>
        <td>http://thewebblend.com/</td>
        <td>s_thewebblend</td>
    </tr>
    <tr>
        <td>Thinkfinity</td>
        <td>http://www.thinkfinity.org/</td>
        <td>s_thinkfinity</td>
    </tr>
    <tr>
        <td>Thisnext</td>
        <td>http://www.thisnext.com/</td>
        <td>s_thisnext</td>
    </tr>
    <tr>
        <td>Tuenti</td>
        <td>http://www.tuenti.com/</td>
        <td>s_tuenti</td>
    </tr>
    <tr>
        <td>Typepad</td>
        <td>http://www.typepad.com/</td>
        <td>s_typepad</td>
    </tr>
    <tr>
        <td>Viadeo</td>
        <td>http://www.viadeo.com/</td>
        <td>s_viadeo</td>
    </tr>
    <tr>
        <td>Virb</td>
        <td>http://virb.com/</td>
        <td>s_virb</td>
    </tr>
    <tr>
        <td>Visitezmonsite</td>
        <td>http://www.visitezmonsite.com/</td>
        <td>s_visitezmonsite</td>
    </tr>
    <tr>
        <td>Vybralisme</td>
        <td>http://vybrali.sme.sk/</td>
        <td>s_vybralisme</td>
    </tr>
    <tr>
        <td>Wirefan</td>
        <td>http://www.wirefan.com/</td>
        <td>s_wirefan</td>
    </tr>
    <tr>
        <td>Wordpress</td>
        <td>http://wordpress.com/</td>
        <td>s_wordpress</td>
    </tr>
    <tr>
        <td>Wowbored</td>
        <td>http://www.wowbored.com/</td>
        <td>s_wowbored</td>
    </tr>
    <tr>
        <td>Wykop</td>
        <td>http://www.wykop.pl/</td>
        <td>s_wykop</td>
    </tr>
    <tr>
        <td>Yahoobkm</td>
        <td>http://bookmarks.yahoo.com/</td>
        <td>s_yahoobkm</td>
    </tr>
    <tr>
        <td>Yahoomail</td>
        <td>http://compose.mail.yahoo.com/</td>
        <td>s_yahoomail</td>
    </tr>
    <tr>
        <td>Yammer</td>
        <td>https://www.yammer.com/</td>
        <td>s_yammer</td>
    </tr>
    <tr>
        <td>Yardbarker</td>
        <td>http://www.yardbarker.com/</td>
        <td>s_yardbarker</td>
    </tr>
    <tr>
        <td>Yigg</td>
        <td>http://www.yigg.de/</td>
        <td>s_yigg</td>
    </tr>
    <tr>
        <td>Yoolink</td>
        <td>http://go.yoolink.to/</td>
        <td>s_yoolink</td>
    </tr>
    <tr>
        <td>Yorumcuyum</td>
        <td>http://www.yorumcuyum.com/</td>
        <td>s_yorumcuyum</td>
    </tr>
    <tr>
        <td>Youmob</td>
        <td>http://youmob.com/</td>
        <td>s_youmob</td>
    </tr>
    <tr>
        <td>Zakladoknet</td>
        <td>http://zakladok.net/</td>
        <td>s_zakladoknet</td>
    </tr>
    <tr>
        <td>Ziczac</td>
        <td>http://ziczac.it/</td>
        <td>s_ziczac</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>https://www.whatsapp.com/</td>
        <td>s_whatsapp</td>
    </tr>

</table>


*Please report me about any bugs.*
