# LanguageNet Grapheme-to-Phoneme Transducers

## Usage

* Download and install
[Phonetisaurus](https://github.com/AdolfVonKleist/Phonetisaurus)

* Get your own copy of the G2Ps: `git clone https://github.com/uiuc-sst/g2ps`

* Test the installation: `phonetisaurus-g2pfst --model=g2ps/models/akan.fst --word=ahyiakwa`
You should see the answer "ahyiakwa	21.7336	a ç i a ɥ a˥".

## Description

* The column "FSTs" is a trained grapheme-to-phoneme transducer for
use with phonetisaurus.  If the available lexicons were large enough
to test the phone error rate (PER), then it is listed in parentheses.
As of this writing, PERs range from 7\% to 45\%.  Note: some of the
trained models exceed git's file size limit, so they're not available
on the github page; you can still find them at
[http://www.isle.illinois.edu/speech_web_lg/data/g2ps/](http://www.isle.illinois.edu/speech_web_lg/data/g2ps/).
Currently those are (american-english, arabic, dutch, french, german,
portuguese, russian, spanish, turkish).

* The column "Pronlexes" lists pronunciation lexicons distributed on
this site; most are just short symbol tables, but a few are longer.

* Other columns are just pointers to sources.

## Acknowledgments

This project was funded from 2016-2019 as part of the
[LanguageNet](http://www.isle.illinois.edu/sst/research/darpa2015/index.html).
Phonetisaurus G2Ps were trained using the lexicons listed here, and
the lexicons in the LanguageNet.  Some languages had other sources:
[Appen BABEL](https://www.iarpa.gov/index.php/research-programs/babel)
lexicons (amharic, assamese, bengali, cebuano, georgian, guarani,
haitian, igbo, javanese, kurdish, lao, lithuanian, luo, mongolian,
pushto, swahili, tagalog, tamil, tok-pisin, turkish, vietnamese, yue,
zulu), [CELEX](https://catalog.ldc.upenn.edu/ldc96l14) (dutch,
english, german), CALLHOME
([egyptian-arabic](https://catalog.ldc.upenn.edu/LDC99L22),
[mandarin](https://catalog.ldc.upenn.edu/LDC96L15),
[spanish](https://catalog.ldc.upenn.edu/LDC96L16)).
	
## Index of data

Copied here from the file index.html.

    <table border=1>
      <tr>
        <th>Codes</th>
        <th>Names</th>
        <th>FSTs</th>
        <th>Pronlexes</th>
        <th>Texts</th>
        <th>Sources</th>
      </tr>
      <tr>
        <td>
          afb<br />
        </td>
        <td>
          Gulf-Arabic<br />
        </td>
        <td>
          <a href="models/gulf-arabic_4_3_4.fst.gz">models/gulf-arabic_4_3_4.fst.gz</a>(19.4)<br />
        </td>
        <td>
          <a href="Gulf-Arabic/QACdict.html">Gulf-Arabic/QACdict.html</a><br />
        </td>
        <td>
        </td>
        <td>
          <a href="http://ifp-08.ifp.uiuc.edu/public/QAC/">http://ifp-08.ifp.uiuc.edu/public/QAC/</a><br />
        </td>
      </tr>
      <tr>
        <td>
          aii<br />
        </td>
        <td>
          Assyrian Neo-Aramaic<br />
        </td>
        <td>
          <a href="models/assyrian-neo-aramaic_2_4_4.fst.gz">models/assyrian-neo-aramaic_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Assyrian-Neo-Aramaic/Assyrian-Neo-Aramaic_wikipedia_symboltable.html">Assyrian-Neo-Aramaic/Assyrian-Neo-Aramaic_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/assyrian.html">sbs-pages/20150418/assyrian.html</a><br />
          <a href="Assyrian-Neo-Aramaic/Assyrian-Neo-Aramaic_swadesh_list.html">Assyrian-Neo-Aramaic/Assyrian-Neo-Aramaic_swadesh_list.html</a><br />
        </td>
        <td>
          <a href="https://en.wikipedia.org/wiki/Assyrian_Neo-Aramaic">https://en.wikipedia.org/wiki/Assyrian_Neo-Aramaic</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/assyrian/">http://www.sbs.com.au/yourlanguage/assyrian/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Afro-Asiatic_languages">http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Afro-Asiatic_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          ain<br />
        </td>
        <td>
          Ainu<br />
        </td>
        <td>
          <a href="models/ainu_4_4_4.fst.gz">models/ainu_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Ainu/Ainu_Katakana_wikipedia_symboltable.html">Ainu/Ainu_Katakana_wikipedia_symboltable.html</a><br />
          <a href="Ainu/Ainu_Latin_wikipedia_symboltable.html">Ainu/Ainu_Latin_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="Ainu/Ainu_swadesh_list.html">Ainu/Ainu_swadesh_list.html</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/196">http://phoible.org/inventories/view/196</a><br />
          <a href="https://en.wikipedia.org/wiki/Ainu_language">https://en.wikipedia.org/wiki/Ainu_language</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Paleosiberian_Swadesh_lists">https://en.wiktionary.org/wiki/Appendix:Paleosiberian_Swadesh_lists</a><br />
        </td>
      </tr>
      <tr>
        <td>
          apc<br />
        </td>
        <td>
          Levantine Arabic<br />
        </td>
        <td>
          <a href="models/levantine-arabic_2_4_4.fst.gz">models/levantine-arabic_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Levantine-Arabic/Levantine-Arabic_wikipedia_symboltable.html">Levantine-Arabic/Levantine-Arabic_wikipedia_symboltable.html</a><br />
          <a href="Levantine-Arabic/ajpdict.html">Levantine-Arabic/ajpdict.html</a><br />
          <a href="Levantine-Arabic/abdeljawad81appC.html">Levantine-Arabic/abdeljawad81appC.html</a><br />
          <a href="Levantine-Arabic/abdeljawad81appD.html">Levantine-Arabic/abdeljawad81appD.html</a><br />
          <a href="Levantine-Arabic/abdeljawad81table3_6.html">Levantine-Arabic/abdeljawad81table3_6.html</a><br />
        </td>
        <td>
          <a href="Levantine-Arabic/Levantine-Arabic_swadesh_list.html">Levantine-Arabic/Levantine-Arabic_swadesh_list.html</a><br />
        </td>
        <td>
          <a href="http://en.wikipedia.org/wiki/Levantine_Arabic">http://en.wikipedia.org/wiki/Levantine_Arabic</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Palestinian_Arabic_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Palestinian_Arabic_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          aka<br />
          ak<br />
        </td>
        <td>
          Akan<br />
        </td>
        <td>
          <a href="models/akan_8_2_2.fst.gz">models/akan_8_2_2.fst.gz</a>(14.0)<br />
        </td>
        <td>
          <a href="Akan/Akan_wikipedia_symboltable.html">Akan/Akan_wikipedia_symboltable.html</a><br />
          <a href="Akan/CABCCAD_dict.html">Akan/CABCCAD_dict.html</a><br />
        </td>
        <td>
          <a href="http://ak.wikipedia.org">http://ak.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/aka">http://phoible.org/languages/aka</a><br />
          <a href="http://en.wikipedia.org/wiki/Akan_language">http://en.wikipedia.org/wiki/Akan_language</a><br />
          <a href="https://www.academia.edu/19685614/A_phone_set_for_an_Akan_Text_to_Speech_System">https://www.academia.edu/19685614/A_phone_set_for_an_Akan_Text_to_Speech_System</a><br />
          <a href="http://archive.phonetics.ucla.edu/Language/AKA/aka_word-list_1971_01.html">http://archive.phonetics.ucla.edu/Language/AKA/aka_word-list_1971_01.html</a><br />
        </td>
      </tr>
      <tr>
        <td>
          amh<br />
          am<br />
        </td>
        <td>
          Amharic<br />
        </td>
        <td>
          <a href="models/amharic_8_2_4.fst.gz">models/amharic_8_2_4.fst.gz</a>(5.7)<br />
        </td>
        <td>
          <a href="Amharic/Amharic_wikipedia_symboltable.html">Amharic/Amharic_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/amharic.html">sbs-pages/20150418/amharic.html</a><br />
          <a href="Amharic/Amharic_swadesh_list.html">Amharic/Amharic_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/am/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/am/</a><br />
          <a href="http://am.wikipedia.org">http://am.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/amh">http://phoible.org/languages/amh</a><br />
          <a href="http://en.wikipedia.org/wiki/Amharic_language">http://en.wikipedia.org/wiki/Amharic_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/amharic/">http://www.sbs.com.au/yourlanguage/amharic/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Afro-Asiatic_languages">http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Afro-Asiatic_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          arb<br />
          ar<br />
        </td>
        <td>
          Arabic<br />
        </td>
        <td>
          <a href="http://isle.illinois.edu/speech_web_lg/data/g2ps/models/arabic.fst">http://isle.illinois.edu/speech_web_lg/data/g2ps/models/arabic.fst</a>
        </td>
        <td>
          <a href="Arabic/Arabic_wikipedia_symboltable.html">Arabic/Arabic_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/arabic.html">sbs-pages/20150418/arabic.html</a><br />
          <a href="Arabic/Arabic_swadesh_list.html">Arabic/Arabic_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/ar/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/ar/</a><br />
          <a href="http://ar.wikipedia.org">http://ar.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://en.wikipedia.org/wiki/Arabic_language">http://en.wikipedia.org/wiki/Arabic_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/arabic?language=ar">http://www.sbs.com.au/yourlanguage/arabic?language=ar</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Afro-Asiatic_languages">http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Afro-Asiatic_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          ary<br />
        </td>
        <td>
          Moroccan Arabic<br />
        </td>
        <td>
        </td>
        <td>
          <a href="Moroccan-Arabic/talmoudi84lex.html">Moroccan-Arabic/talmoudi84lex.html</a><br />
        </td>
        <td>
          <a href="Moroccan-Arabic/Moroccan-Arabic_swadesh_list.html">Moroccan-Arabic/Moroccan-Arabic_swadesh_list.html</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/ary">http://phoible.org/languages/ary</a><br />
          <a href="https://en.wikipedia.org/wiki/Moroccan_Arabic">https://en.wikipedia.org/wiki/Moroccan_Arabic</a><br />
        </td>
      </tr>
      <tr>
        <td>
          arz<br />
        </td>
        <td>
          Egyptian Arabic<br />
        </td>
        <td>
          <a href="models/egyptian-arabic_4_2_2.fst.gz">models/egyptian-arabic_4_2_2.fst.gz</a>(21.5)<br />
        </td>
        <td>
          <a href="Egyptian-Arabic/Egyptian-Arabic_wikipedia_symboltable.html">Egyptian-Arabic/Egyptian-Arabic_wikipedia_symboltable.html</a><br />
          <a href="Egyptian-Arabic/schmidt75dict.html">Egyptian-Arabic/schmidt75dict.html</a><br />
          <a href="Egyptian-Arabic/schmidt75verbstems.html">Egyptian-Arabic/schmidt75verbstems.html</a><br />
        </td>
        <td>
          <a href="Egyptian-Arabic/Egyptian-Arabic_swadesh_list.html">Egyptian-Arabic/Egyptian-Arabic_swadesh_list.html</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/arz">http://phoible.org/languages/arz</a><br />
          <a href="http://en.wikipedia.org/wiki/Egyptian_Arabic">http://en.wikipedia.org/wiki/Egyptian_Arabic</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Egyptian_Arabic_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Egyptian_Arabic_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          asm<br />
          as<br />
        </td>
        <td>
          Assamese<br />
        </td>
        <td>
          <a href="models/assamese_4_2_3.fst.gz">models/assamese_4_2_3.fst.gz</a>(5.8)<br />
        </td>
        <td>
          <a href="Assamese/Assamese_wikipedia_symboltable.html">Assamese/Assamese_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://as.wikipedia.org">http://as.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/asm">http://phoible.org/languages/asm</a><br />
          <a href="http://en.wikipedia.org/wiki/Assamese_language">http://en.wikipedia.org/wiki/Assamese_language</a><br />
          <a href="https://en.wikipedia.org/wiki/Indo-Iranian_languages">https://en.wikipedia.org/wiki/Indo-Iranian_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          aym<br />
          ay<br />
        </td>
        <td>
          Aymara<br />
        </td>
        <td>
          <a href="models/aymara_2_4_4.fst.gz">models/aymara_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Aymara/Aymara_wikipedia_symboltable.html">Aymara/Aymara_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://ay.wikipedia.org">http://ay.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/ayr">http://phoible.org/languages/ayr</a><br />
        </td>
      </tr>
      <tr>
        <td>
          aze<br />
          az<br />
        </td>
        <td>
          Azerbaijani<br />
        </td>
        <td>
          <a href="models/azerbaijani_4_3_4.fst.gz">models/azerbaijani_4_3_4.fst.gz</a>(0.1)<br />
        </td>
        <td>
          <a href="Azerbaijani/Azerbaijani_wikipedia_symboltable.html">Azerbaijani/Azerbaijani_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://az.wikipedia.org">http://az.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/187">http://phoible.org/inventories/view/187</a><br />
          <a href="https://en.wikipedia.org/wiki/Azerbaijani_alphabet">https://en.wikipedia.org/wiki/Azerbaijani_alphabet</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Turkic_Swadesh_lists">https://en.wiktionary.org/wiki/Appendix:Turkic_Swadesh_lists</a><br />
        </td>
      </tr>
      <tr>
        <td>
          bam<br />
          bm<br />
        </td>
        <td>
          Bambara<br />
        </td>
        <td>
          <a href="models/bambara_2_4_4.fst.gz">models/bambara_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Bambara/Bambara_wikipedia_symboltable.html">Bambara/Bambara_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://bm.wikipedia.org">http://bm.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/bam">http://phoible.org/languages/bam</a><br />
          <a href="https://en.wikipedia.org/wiki/Bambara_language">https://en.wikipedia.org/wiki/Bambara_language</a><br />
        </td>
      </tr>
      <tr>
        <td>
          bel<br />
          be<br />
        </td>
        <td>
          Belarusian<br />
        </td>
        <td>
          <a href="models/belarusian_2_4_4.fst.gz">models/belarusian_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Belarusian/Belarusian_wikipedia_symboltable.html">Belarusian/Belarusian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://be.wikipedia.org">http://be.wikipedia.org</a><br />
        </td>
        <td>
          <a href="https://en.wikipedia.org/wiki/Belarusian_alphabet">https://en.wikipedia.org/wiki/Belarusian_alphabet</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Belarusian_Swadesh_list">https://en.wiktionary.org/wiki/Appendix:Belarusian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          ben<br />
          bn<br />
        </td>
        <td>
          Bengali<br />
          Bangla<br />
        </td>
        <td>
          <a href="models/bengali_4_3_2.fst.gz">models/bengali_4_3_2.fst.gz</a>(7.7)<br />
        </td>
        <td>
          <a href="Bengali/Bengali_wikipedia_symboltable.html">Bengali/Bengali_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="Bengali/Bengali_swadesh_list.html">Bengali/Bengali_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/bn/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/bn/</a><br />
          <a href="http://bn.wikipedia.org">http://bn.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/ben">http://phoible.org/languages/ben</a><br />
          <a href="http://en.wikipedia.org/wiki/Bengali_language">http://en.wikipedia.org/wiki/Bengali_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/bangla/">http://www.sbs.com.au/yourlanguage/bangla/</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Indo-Aryan_Swadesh_lists">https://en.wiktionary.org/wiki/Appendix:Indo-Aryan_Swadesh_lists</a><br />
        </td>
      </tr>
      <tr>
        <td>
          tzm<br />
        </td>
        <td>
          Central Atlas Tamazight<br />
        </td>
        <td>
          <a href="models/berber_8_2_2.fst.gz">models/berber_8_2_2.fst.gz</a>(22.2)<br />
        </td>
        <td>
          <a href="Berber/Berber_Latin_wikipedia_symboltable.html">Berber/Berber_Latin_wikipedia_symboltable.html</a><br />
          <a href="Berber/Berber_Tifinagh_wikipedia_symboltable.html">Berber/Berber_Tifinagh_wikipedia_symboltable.html</a><br />
        </td>
        <td>
        </td>
        <td>
          <a href="http://en.wikipedia.org/wiki/Berber_languages">http://en.wikipedia.org/wiki/Berber_languages</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Afro-Asiatic_languages">http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Afro-Asiatic_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          bod<br />
          bo<br />
        </td>
        <td>
          Tibetan<br />
        </td>
        <td>
          <a href="models/tibetan_4_4_4.fst.gz">models/tibetan_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Tibetan/Tibetan_wikipedia_symboltable.html">Tibetan/Tibetan_wikipedia_symboltable.html</a><br />
        </td>
        <td>
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/1067">http://phoible.org/inventories/view/1067</a><br />
        </td>
      </tr>
      <tr>
        <td>
          bos<br />
          bs<br />
        </td>
        <td>
          Bosnian<br />
        </td>
        <td>
          <a href="models/bosnian_2_4_4.fst.gz">models/bosnian_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Bosnian/Bosnian_wikipedia_symboltable.html">Bosnian/Bosnian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/bosnian.html">sbs-pages/20150418/bosnian.html</a><br />
          <a href="Bosnian/Bosnian_swadesh_list.html">Bosnian/Bosnian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/bs/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/bs/</a><br />
          <a href="http://bs.wikipedia.org">http://bs.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://en.wikipedia.org/wiki/Bosnian_language">http://en.wikipedia.org/wiki/Bosnian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/bosnian/">http://www.sbs.com.au/yourlanguage/bosnian/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Serbo-Croatian_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Serbo-Croatian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          bul<br />
          bg<br />
        </td>
        <td>
          Bulgarian<br />
        </td>
        <td>
          <a href="models/bulgarian_2_4_4.fst.gz">models/bulgarian_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Bulgarian/Bulgarian_wikipedia_symboltable.html">Bulgarian/Bulgarian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/bulgarian.html">sbs-pages/20150418/bulgarian.html</a><br />
          <a href="Bulgarian/Bulgarian_swadesh_list.html">Bulgarian/Bulgarian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/bg/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/bg/</a><br />
          <a href="http://bg.wikipedia.org">http://bg.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/bul">http://phoible.org/languages/bul</a><br />
          <a href="http://en.wikipedia.org/wiki/Bulgarian_language">http://en.wikipedia.org/wiki/Bulgarian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/bulgarian/">http://www.sbs.com.au/yourlanguage/bulgarian/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Bulgarian_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Bulgarian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          ceb<br />
        </td>
        <td>
          Cebuano<br />
        </td>
        <td>
          <a href="models/cebuano_4_3_2.fst.gz">models/cebuano_4_3_2.fst.gz</a>(15.9)<br />
        </td>
        <td>
          <a href="Cebuano/Cebuano_wikipedia_symboltable.html">Cebuano/Cebuano_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://ceb.wikipedia.org">http://ceb.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/1692">http://phoible.org/inventories/view/1692</a><br />
          <a href="https://en.wikipedia.org/wiki/Abakada_alphabet">https://en.wikipedia.org/wiki/Abakada_alphabet</a><br />
        </td>
      </tr>
      <tr>
        <td>
          ces<br />
          cs<br />
        </td>
        <td>
          Czech<br />
        </td>
        <td>
          <a href="models/czech_4_4_4.fst.gz">models/czech_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Czech/Czech_wikipedia_symboltable.html">Czech/Czech_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/czech.html">sbs-pages/20150418/czech.html</a><br />
          <a href="Czech/Czech_swadesh_list.html">Czech/Czech_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/cs/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/cs/</a><br />
          <a href="http://cs.wikipedia.org">http://cs.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/ces">http://phoible.org/languages/ces</a><br />
          <a href="http://en.wikipedia.org/wiki/Czech_language">http://en.wikipedia.org/wiki/Czech_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/czech/">http://www.sbs.com.au/yourlanguage/czech/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Czech_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Czech_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          cmn<br />
          zh<br />
        </td>
        <td>
          Mandarin_Chinese<br />
        </td>
        <td>
          <a href="models/mandarin_2_4_4.fst.gz">models/mandarin_2_4_4.fst.gz</a>(3.9)<br />
        </td>
        <td>
          <a href="Mandarin/Mandarin_Pinyin_wikipedia_symboltable.html">Mandarin/Mandarin_Pinyin_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/mandarin.html">sbs-pages/20150418/mandarin.html</a><br />
          <a href="Mandarin/Mandarin_swadesh_list.html">Mandarin/Mandarin_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/zh/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/zh/</a><br />
          <a href="http://zh.wikipedia.org">http://zh.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/cmn">http://phoible.org/languages/cmn</a><br />
          <a href="https://en.wikipedia.org/wiki/Pinyin">https://en.wikipedia.org/wiki/Pinyin</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/mandarin?language=zh-hans">http://www.sbs.com.au/yourlanguage/mandarin?language=zh-hans</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Mandarin_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Mandarin_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          dan<br />
          da<br />
        </td>
        <td>
          Danish<br />
        </td>
        <td>
          <a href="models/danish_2_4_4.fst.gz">models/danish_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Danish/Danish_wikipedia_symboltable.html">Danish/Danish_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/danish.html">sbs-pages/20150418/danish.html</a><br />
          <a href="Danish/Danish_swadesh_list.html">Danish/Danish_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/da/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/da/</a><br />
          <a href="http://da.wikipedia.org">http://da.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/499">http://phoible.org/inventories/view/499</a><br />
          <a href="http://en.wikipedia.org/wiki/Danish_language">http://en.wikipedia.org/wiki/Danish_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/danish/">http://www.sbs.com.au/yourlanguage/danish/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Danish_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Danish_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          deu<br />
          de<br />
        </td>
        <td>
          German<br />
        </td>
        <td>
          <a href="http://isle.illinois.edu/speech_web_lg/data/g2ps/models/german.fst">http://isle.illinois.edu/speech_web_lg/data/g2ps/models/german.fst</a>
        </td>
        <td>
          <a href="German/German_wikipedia_symboltable.html">German/German_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/german.html">sbs-pages/20150418/german.html</a><br />
          <a href="German/German_swadesh_list.html">German/German_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/de/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/de/</a><br />
          <a href="http://de.wikipedia.org">http://de.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/deu">http://phoible.org/languages/deu</a><br />
          <a href="http://en.wikipedia.org/wiki/German_language">http://en.wikipedia.org/wiki/German_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/german/">http://www.sbs.com.au/yourlanguage/german/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:German_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:German_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          din<br />
        </td>
        <td>
          Dinka<br />
        </td>
        <td>
          <a href="models/dinka_2_4_4.fst.gz">models/dinka_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Dinka/Dinka_wikipedia_symboltable.html">Dinka/Dinka_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/dinka.html">sbs-pages/20150418/dinka.html</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/din">http://phoible.org/languages/din</a><br />
          <a href="http://en.wikipedia.org/wiki/Dinka_language">http://en.wikipedia.org/wiki/Dinka_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/dinka/">http://www.sbs.com.au/yourlanguage/dinka/</a><br />
        </td>
      </tr>
      <tr>
        <td>
          ell<br />
          el<br />
        </td>
        <td>
          Greek<br />
        </td>
        <td>
          <a href="models/greek_2_2_2.fst.gz">models/greek_2_2_2.fst.gz</a>(9.9)<br />
        </td>
        <td>
          <a href="Greek/Greek_wikipedia_symboltable.html">Greek/Greek_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/greek.html">sbs-pages/20150418/greek.html</a><br />
          <a href="Greek/Greek_swadesh_list.html">Greek/Greek_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/el/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/el/</a><br />
          <a href="http://el.wikipedia.org">http://el.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/ell">http://phoible.org/languages/ell</a><br />
          <a href="http://en.wikipedia.org/wiki/Greek_language">http://en.wikipedia.org/wiki/Greek_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/greek?language=el">http://www.sbs.com.au/yourlanguage/greek?language=el</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Greek_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Greek_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          eng<br />
        </td>
        <td>
          English<br />
        </td>
        <td>
          <a href="models/english_4_2_2.fst.gz">models/english_4_2_2.fst.gz</a>(14.3)<br />
          <a href="http://isle.illinois.edu/speech_web_lg/data/g2ps/models/american-english.fst">http://isle.illinois.edu/speech_web_lg/data/g2ps/models/american-english.fst</a>
        </td>
        <td>
          <a href="English/American-English_wikipedia_symboltable.html">English/American-English_wikipedia_symboltable.html</a><br />
          <a href="English/ISLEdict.html">English/ISLEdict.html</a><br />
        </td>
        <td>
          <a href="English/English_swadesh_list.html">English/English_swadesh_list.html</a><br />
          <a href="http://en.wikipedia.org">http://en.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/eng">http://phoible.org/languages/eng</a><br />
          <a href="http://en.wikipedia.org/wiki/English_language">http://en.wikipedia.org/wiki/English_language</a><br />
          <a href="http://www.speech.cs.cmu.edu/cgi-bin/cmudict">http://www.speech.cs.cmu.edu/cgi-bin/cmudict</a><br />
          <a href="https://github.com/Hyneman/moby-project">https://github.com/Hyneman/moby-project</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Germanic_languages">http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Germanic_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          est<br />
          et<br />
        </td>
        <td>
          Estonian<br />
        </td>
        <td>
          <a href="models/estonian_2_4_4.fst.gz">models/estonian_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Estonian/Estonian_wikipedia_symboltable.html">Estonian/Estonian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/estonian.html">sbs-pages/20150418/estonian.html</a><br />
          <a href="Estonian/Estonian_swadesh_list.html">Estonian/Estonian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/et/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/et/</a><br />
          <a href="http://et.wikipedia.org">http://et.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://en.wikipedia.org/wiki/Estonian_language">http://en.wikipedia.org/wiki/Estonian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/estonian/">http://www.sbs.com.au/yourlanguage/estonian/</a><br />
        </td>
      </tr>
      <tr>
        <td>
          fij<br />
          fj<br />
        </td>
        <td>
          Fijian<br />
        </td>
        <td>
          <a href="models/fijian_4_4_4.fst.gz">models/fijian_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Fijian/Fijian_wikipedia_symboltable.html">Fijian/Fijian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/fijian.html">sbs-pages/20150418/fijian.html</a><br />
          <a href="Fijian/Fijian_swadesh_list.html">Fijian/Fijian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/fj/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/fj/</a><br />
          <a href="http://fj.wikipedia.org">http://fj.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://en.wikipedia.org/wiki/Fijian_language">http://en.wikipedia.org/wiki/Fijian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/fijian/">http://www.sbs.com.au/yourlanguage/fijian/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Fijian_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Fijian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          fil<br />
          tl<br />
        </td>
        <td>
          Filipino<br />
        </td>
        <td>
          <a href="models/filipino_4_4_4.fst.gz">models/filipino_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Filipino/Filipino_wikipedia_symboltable.html">Filipino/Filipino_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/filipino.html">sbs-pages/20150418/filipino.html</a><br />
          <a href="Filipino/Filipino_swadesh_list.html">Filipino/Filipino_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/tl/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/tl/</a><br />
          <a href="http://tl.wikipedia.org">http://tl.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/fil">http://phoible.org/languages/fil</a><br />
          <a href="http://en.wikipedia.org/wiki/Filipino_language">http://en.wikipedia.org/wiki/Filipino_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/filipino?language=fil">http://www.sbs.com.au/yourlanguage/filipino?language=fil</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Tagalog_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Tagalog_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          fin<br />
          fi<br />
        </td>
        <td>
          Finnish<br />
        </td>
        <td>
          <a href="models/finnish_2_4_4.fst.gz">models/finnish_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Finnish/Finnish_wikipedia_symboltable.html">Finnish/Finnish_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/finnish.html">sbs-pages/20150418/finnish.html</a><br />
          <a href="Finnish/Finnish_swadesh_list.html">Finnish/Finnish_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/fi/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/fi/</a><br />
          <a href="http://fi.wikipedia.org">http://fi.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/fin">http://phoible.org/languages/fin</a><br />
          <a href="http://en.wikipedia.org/wiki/Finnish_language">http://en.wikipedia.org/wiki/Finnish_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/finnish/">http://www.sbs.com.au/yourlanguage/finnish/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Uralic_languages">http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Uralic_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          fra<br />
          fr<br />
        </td>
        <td>
          French<br />
        </td>
        <td>
          <a href="http://isle.illinois.edu/speech_web_lg/data/g2ps/models/french.fst">http://isle.illinois.edu/speech_web_lg/data/g2ps/models/french.fst</a>
        </td>
        <td>
          <a href="French/French_wikipedia_symboltable.html">French/French_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/french.html">sbs-pages/20150418/french.html</a><br />
          <a href="French/French_swadesh_list.html">French/French_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/fr/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/fr/</a><br />
          <a href="http://fr.wikipedia.org">http://fr.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/fra">http://phoible.org/languages/fra</a><br />
          <a href="http://en.wikipedia.org/wiki/French_language">http://en.wikipedia.org/wiki/French_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/french/">http://www.sbs.com.au/yourlanguage/french/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:French_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:French_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          ful<br />
        </td>
        <td>
          Fulah<br />
        </td>
        <td>
          <a href="models/fulah_4_2_2.fst.gz">models/fulah_4_2_2.fst.gz</a>(5.5)<br />
        </td>
        <td>
          <a href="Fulah/Fulah_wikipedia_symboltable.html">Fulah/Fulah_wikipedia_symboltable.html</a><br />
        </td>
        <td>
        </td>
        <td>
          <a href="http://phoible.org/languages/fuh">http://phoible.org/languages/fuh</a><br />
          <a href="https://en.wikipedia.org/wiki/Fula_language">https://en.wikipedia.org/wiki/Fula_language</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Niger-Congo_Swadesh_lists">https://en.wiktionary.org/wiki/Appendix:Niger-Congo_Swadesh_lists</a><br />
        </td>
      </tr>
      <tr>
        <td>
          grn<br />
          gn<br />
        </td>
        <td>
          Guarani<br />
        </td>
        <td>
          <a href="models/guarani_4_2_2.fst.gz">models/guarani_4_2_2.fst.gz</a>(8.8)<br />
        </td>
        <td>
          <a href="Guarani/Guarani_wikipedia_symboltable.html">Guarani/Guarani_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://gn.wikipedia.org">http://gn.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/2077">http://phoible.org/inventories/view/2077</a><br />
          <a href="http://en.wikipedia.org/wiki/Guarani_language">http://en.wikipedia.org/wiki/Guarani_language</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Guaran%C3%AD_Swadesh_list">https://en.wiktionary.org/wiki/Appendix:Guaran%C3%AD_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          guj<br />
          gu<br />
        </td>
        <td>
          Gujarati<br />
        </td>
        <td>
          <a href="models/gujarati_4_4_4.fst.gz">models/gujarati_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Gujarati/Gujarati_wikipedia_symboltable.html">Gujarati/Gujarati_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/gujarati.html">sbs-pages/20150418/gujarati.html</a><br />
          <a href="Gujarati/Gujarati_swadesh_list.html">Gujarati/Gujarati_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/gu/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/gu/</a><br />
          <a href="http://gu.wikipedia.org">http://gu.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/guj">http://phoible.org/languages/guj</a><br />
          <a href="http://en.wikipedia.org/wiki/Gujarati_language">http://en.wikipedia.org/wiki/Gujarati_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/gujarati?language=gu">http://www.sbs.com.au/yourlanguage/gujarati?language=gu</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Indo-Aryan_Swadesh_lists">https://en.wiktionary.org/wiki/Appendix:Indo-Aryan_Swadesh_lists</a><br />
        </td>
      </tr>
      <tr>
        <td>
          hat<br />
          ht<br />
        </td>
        <td>
          Haitian Creole<br />
        </td>
        <td>
          <a href="models/haitian_8_3_3.fst.gz">models/haitian_8_3_3.fst.gz</a>(2.7)<br />
        </td>
        <td>
          <a href="Haitian/Haitian_wikipedia_symboltable.html">Haitian/Haitian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
        </td>
        <td>
          <a href="http://en.wikipedia.org/wiki/Haitian_Creole">http://en.wikipedia.org/wiki/Haitian_Creole</a><br />
        </td>
      </tr>
      <tr>
        <td>
          hau<br />
        </td>
        <td>
          Hausa<br />
        </td>
        <td>
          <a href="models/hausa_2_2_2.fst.gz">models/hausa_2_2_2.fst.gz</a>(0.1)<br />
        </td>
        <td>
          <a href="Hausa/Hausa_Ajami_wikipedia_symboltable.html">Hausa/Hausa_Ajami_wikipedia_symboltable.html</a><br />
          <a href="Hausa/Hausa_Boko_wikipedia_symboltable.html">Hausa/Hausa_Boko_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://ha.wikipedia.org">http://ha.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/hau">http://phoible.org/languages/hau</a><br />
          <a href="http://en.wikipedia.org/wiki/Hausa_language">http://en.wikipedia.org/wiki/Hausa_language</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Hausa_Swadesh_list">https://en.wiktionary.org/wiki/Appendix:Hausa_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          heb<br />
          he<br />
        </td>
        <td>
          Hebrew<br />
        </td>
        <td>
          <a href="models/hebrew_2_4_4.fst.gz">models/hebrew_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Hebrew/Hebrew_wikipedia_symboltable.html">Hebrew/Hebrew_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/hebrew.html">sbs-pages/20150418/hebrew.html</a><br />
          <a href="Hebrew/Hebrew_swadesh_list.html">Hebrew/Hebrew_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/he/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/he/</a><br />
          <a href="http://he.wikipedia.org">http://he.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/heb">http://phoible.org/languages/heb</a><br />
          <a href="http://en.wikipedia.org/wiki/Hebrew_language">http://en.wikipedia.org/wiki/Hebrew_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/hebrew/">http://www.sbs.com.au/yourlanguage/hebrew/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Afro-Asiatic_languages">http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Afro-Asiatic_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          hin<br />
          hi<br />
        </td>
        <td>
          Hindi<br />
        </td>
        <td>
          <a href="models/hindi_4_2_2.fst.gz">models/hindi_4_2_2.fst.gz</a>(8.0)<br />
        </td>
        <td>
          <a href="Hindi/Hindi_wikipedia_symboltable.html">Hindi/Hindi_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/hindi.html">sbs-pages/20150418/hindi.html</a><br />
          <a href="Hindi/Hindi_swadesh_list.html">Hindi/Hindi_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/hi/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/hi/</a><br />
          <a href="http://hi.wikipedia.org">http://hi.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/hin">http://phoible.org/languages/hin</a><br />
          <a href="http://en.wikipedia.org/wiki/Hindi_language">http://en.wikipedia.org/wiki/Hindi_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/hindi?language=hi">http://www.sbs.com.au/yourlanguage/hindi?language=hi</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Hindi_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Hindi_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          hmv<br />
        </td>
        <td>
          Hmong<br />
        </td>
        <td>
          <a href="models/hmong-dô_4_2_2.fst.gz">models/hmong-dô_4_2_2.fst.gz</a>(23.6)<br />
        </td>
        <td>
          <a href="Hmong-Dô/Hmong-Dô_wikipedia_symboltable.txt">Hmong-Dô/Hmong-Dô_wikipedia_symboltable.txt</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/hmong.html">sbs-pages/20150418/hmong.html</a><br />
          <a href="Hmong-Dô/Hmong-Dô_swadesh_list.html">Hmong-Dô/Hmong-Dô_swadesh_list.html</a><br />
        </td>
        <td>
          <a href="http://en.wikipedia.org/wiki/Hmong_Daw">http://en.wikipedia.org/wiki/Hmong_Daw</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/hmong/">http://www.sbs.com.au/yourlanguage/hmong/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:White_Hmong_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:White_Hmong_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          hrv<br />
          hr<br />
        </td>
        <td>
          Croatian<br />
        </td>
        <td>
          <a href="models/croatian_2_2_2.fst.gz">models/croatian_2_2_2.fst.gz</a>(0.3)<br />
        </td>
        <td>
          <a href="Croatian/Croatian_wikipedia_symboltable.html">Croatian/Croatian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/croatian.html">sbs-pages/20150418/croatian.html</a><br />
          <a href="Croatian/Croatian_swadesh_list.html">Croatian/Croatian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/hr/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/hr/</a><br />
          <a href="http://hr.wikipedia.org">http://hr.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/hrv">http://phoible.org/languages/hrv</a><br />
          <a href="http://en.wikipedia.org/wiki/Croatian_language">http://en.wikipedia.org/wiki/Croatian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/croatian/">http://www.sbs.com.au/yourlanguage/croatian/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Serbo-Croatian_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Serbo-Croatian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          hun<br />
          hu<br />
        </td>
        <td>
          Hungarian<br />
        </td>
        <td>
          <a href="models/hungarian_2_4_2.fst.gz">models/hungarian_2_4_2.fst.gz</a>(0.6)<br />
        </td>
        <td>
          <a href="Hungarian/Hungarian_wikipedia_symboltable.html">Hungarian/Hungarian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/hungarian.html">sbs-pages/20150418/hungarian.html</a><br />
          <a href="Hungarian/Hungarian_swadesh_list.html">Hungarian/Hungarian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/hu/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/hu/</a><br />
          <a href="http://hu.wikipedia.org">http://hu.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/hun">http://phoible.org/languages/hun</a><br />
          <a href="http://en.wikipedia.org/wiki/Hungarian_language">http://en.wikipedia.org/wiki/Hungarian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/hungarian/">http://www.sbs.com.au/yourlanguage/hungarian/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Hungarian_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Hungarian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          hye<br />
          hy<br />
        </td>
        <td>
          Armenian<br />
        </td>
        <td>
          <a href="models/armenian_4_2_2.fst.gz">models/armenian_4_2_2.fst.gz</a>(16.2)<br />
        </td>
        <td>
          <a href="Armenian/Armenian_wikipedia_symboltable.html">Armenian/Armenian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/armenian.html">sbs-pages/20150418/armenian.html</a><br />
          <a href="Armenian/Armenian_swadesh_list.html">Armenian/Armenian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/hy/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/hy/</a><br />
          <a href="http://hy.wikipedia.org">http://hy.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/hye">http://phoible.org/languages/hye</a><br />
          <a href="http://en.wikipedia.org/wiki/Armenian_language">http://en.wikipedia.org/wiki/Armenian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/armenian/">http://www.sbs.com.au/yourlanguage/armenian/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Armenian_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Armenian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          ibo<br />
          ig<br />
        </td>
        <td>
          Igbo<br />
        </td>
        <td>
          <a href="models/igbo_2_3_4.fst.gz">models/igbo_2_3_4.fst.gz</a>(22.4)<br />
        </td>
        <td>
          <a href="Igbo/Igbo_wikipedia_symboltable.html">Igbo/Igbo_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://ig.wikipedia.org">http://ig.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/143">http://phoible.org/inventories/view/143</a><br />
          <a href="https://en.wikipedia.org/wiki/Igbo_language">https://en.wikipedia.org/wiki/Igbo_language</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Niger-Congo_Swadesh_lists">https://en.wiktionary.org/wiki/Appendix:Niger-Congo_Swadesh_lists</a><br />
        </td>
      </tr>
      <tr>
        <td>
          ind<br />
          id<br />
        </td>
        <td>
          Indonesian<br />
        </td>
        <td>
          <a href="models/indonesian_2_4_4.fst.gz">models/indonesian_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Indonesian/Indonesian_wikipedia_symboltable.html">Indonesian/Indonesian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/indonesian.html">sbs-pages/20150418/indonesian.html</a><br />
          <a href="Indonesian/Indonesian_swadesh_list.html">Indonesian/Indonesian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/id/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/id/</a><br />
          <a href="http://id.wikipedia.org">http://id.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/ind">http://phoible.org/languages/ind</a><br />
          <a href="http://en.wikipedia.org/wiki/Indonesian_language">http://en.wikipedia.org/wiki/Indonesian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/indonesian?language=id">http://www.sbs.com.au/yourlanguage/indonesian?language=id</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Indonesian_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Indonesian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          ita<br />
          it<br />
        </td>
        <td>
          Italian<br />
        </td>
        <td>
          <a href="models/italian_8_2_3.fst.gz">models/italian_8_2_3.fst.gz</a>(10.1)<br />
        </td>
        <td>
          <a href="Italian/Italian_wikipedia_symboltable.html">Italian/Italian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/italian.html">sbs-pages/20150418/italian.html</a><br />
          <a href="Italian/Italian_swadesh_list.html">Italian/Italian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/it/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/it/</a><br />
          <a href="http://it.wikipedia.org">http://it.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/ita">http://phoible.org/languages/ita</a><br />
          <a href="http://en.wikipedia.org/wiki/Italian_language">http://en.wikipedia.org/wiki/Italian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/italian?language=it">http://www.sbs.com.au/yourlanguage/italian?language=it</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Italian_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Italian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          jav<br />
          jv<br />
        </td>
        <td>
          Javanese<br />
        </td>
        <td>
          <a href="models/javanese_4_2_2.fst.gz">models/javanese_4_2_2.fst.gz</a>(9.8)<br />
        </td>
        <td>
          <a href="Javanese/Javanese_Latin_wikipedia_symboltable.html">Javanese/Javanese_Latin_wikipedia_symboltable.html</a><br />
          <a href="Javanese/Javanese_Hanacarakan_wikipedia_symboltable.html">Javanese/Javanese_Hanacarakan_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://jv.wikipedia.org">http://jv.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/1675">http://phoible.org/inventories/view/1675</a><br />
          <a href="https://en.wikipedia.org/wiki/Javanese_script">https://en.wikipedia.org/wiki/Javanese_script</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Austronesian_Swadesh_lists">https://en.wiktionary.org/wiki/Appendix:Austronesian_Swadesh_lists</a><br />
        </td>
      </tr>
      <tr>
        <td>
          jpn<br />
          ja<br />
        </td>
        <td>
          Japanese<br />
        </td>
        <td>
          <a href="models/japanese_4_4_4.fst.gz">models/japanese_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Japanese/Japanese_wikipedia_symboltable.html">Japanese/Japanese_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/japanese.html">sbs-pages/20150418/japanese.html</a><br />
          <a href="Japanese/Japanese_swadesh_list.html">Japanese/Japanese_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/ja/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/ja/</a><br />
          <a href="http://ja.wikipedia.org">http://ja.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/jpn">http://phoible.org/languages/jpn</a><br />
          <a href="http://en.wikipedia.org/wiki/Japanese_language">http://en.wikipedia.org/wiki/Japanese_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/japanese/">http://www.sbs.com.au/yourlanguage/japanese/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Japanese_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Japanese_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          kan<br />
          kn<br />
        </td>
        <td>
          Kannada<br />
        </td>
        <td>
          <a href="models/kannada_4_4_4.fst.gz">models/kannada_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Kannada/Kannada_wikipedia_symboltable.html">Kannada/Kannada_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/kannada.html">sbs-pages/20150418/kannada.html</a><br />
          <a href="Kannada/Kannada_swadesh_list.html">Kannada/Kannada_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/kn/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/kn/</a><br />
          <a href="http://kn.wikipedia.org">http://kn.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/kan">http://phoible.org/languages/kan</a><br />
          <a href="http://en.wikipedia.org/wiki/Kannada_language">http://en.wikipedia.org/wiki/Kannada_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/kannada/">http://www.sbs.com.au/yourlanguage/kannada/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Dravidian_languages">http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Dravidian_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          kat<br />
          ka<br />
        </td>
        <td>
          Georgian<br />
        </td>
        <td>
          <a href="models/georgian_4_2_3.fst.gz">models/georgian_4_2_3.fst.gz</a>(2.2)<br />
        </td>
        <td>
          <a href="Georgian/Georgian_Mkhedruli_wikipedia_symboltable.html">Georgian/Georgian_Mkhedruli_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://ka.wikipedia.org">http://ka.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/5">http://phoible.org/inventories/view/5</a><br />
          <a href="https://en.wikipedia.org/wiki/Georgian_scripts">https://en.wikipedia.org/wiki/Georgian_scripts</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Georgian_Swadesh_list">https://en.wiktionary.org/wiki/Appendix:Georgian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          kaz<br />
          kk<br />
        </td>
        <td>
          Kazakh<br />
        </td>
        <td>
          <a href="models/kazakh_2_3_2.fst.gz">models/kazakh_2_3_2.fst.gz</a>(0.4)<br />
        </td>
        <td>
          <a href="Kazakh/Kazakh_Arabic_wikipedia_symboltable.html">Kazakh/Kazakh_Arabic_wikipedia_symboltable.html</a><br />
          <a href="Kazakh/Kazakh_Cyrillic_wikipedia_symboltable.html">Kazakh/Kazakh_Cyrillic_wikipedia_symboltable.html</a><br />
          <a href="Kazakh/Kazakh_Latin_wikipedia_symboltable.html">Kazakh/Kazakh_Latin_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="Kazakh/Kazakh_swadesh_list.html">Kazakh/Kazakh_swadesh_list.html</a><br />
          <a href="http://kk.wikipedia.org">http://kk.wikipedia.org</a><br />
        </td>
        <td>
          <a href="https://en.wikipedia.org/wiki/Kazakh_alphabets">https://en.wikipedia.org/wiki/Kazakh_alphabets</a><br />
          <a href="https://en.wikipedia.org/wiki/Turkic_languages">https://en.wikipedia.org/wiki/Turkic_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          khm<br />
          km<br />
        </td>
        <td>
          Khmer<br />
        </td>
        <td>
          <a href="models/khmer_4_4_4.fst.gz">models/khmer_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Khmer/Khmer_wikipedia_symboltable.html">Khmer/Khmer_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/khmer.html">sbs-pages/20150418/khmer.html</a><br />
          <a href="Khmer/Khmer_swadesh_list.html">Khmer/Khmer_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/km/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/km/</a><br />
          <a href="http://km.wikipedia.org">http://km.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/khm">http://phoible.org/languages/khm</a><br />
          <a href="http://en.wikipedia.org/wiki/Khmer_language">http://en.wikipedia.org/wiki/Khmer_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/khmer/">http://www.sbs.com.au/yourlanguage/khmer/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Khmer_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Khmer_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          kik<br />
          ki<br />
        </td>
        <td>
          Kikuyu<br />
        </td>
        <td>
          <a href="models/kikuyu_2_4_4.fst.gz">models/kikuyu_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Kikuyu/Kikuyu_wikipedia_symboltable.html">Kikuyu/Kikuyu_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://ki.wikipedia.org">http://ki.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/748">http://phoible.org/inventories/view/748</a><br />
          <a href="https://en.wikipedia.org/wiki/Kikuyu_language">https://en.wikipedia.org/wiki/Kikuyu_language</a><br />
        </td>
      </tr>
      <tr>
        <td>
          kin<br />
          rw<br />
        </td>
        <td>
          Kinyarwanda<br />
        </td>
        <td>
          <a href="models/kinyarwanda_4_4_4.fst.gz">models/kinyarwanda_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Kinyarwanda/Kinyarwanda_wikipedia_symboltable.html">Kinyarwanda/Kinyarwanda_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://rw.wikipedia.org/">http://rw.wikipedia.org/</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/911">http://phoible.org/inventories/view/911</a><br />
          <a href="https://en.wikipedia.org/wiki/Kinyarwanda">https://en.wikipedia.org/wiki/Kinyarwanda</a><br />
        </td>
      </tr>
      <tr>
        <td>
          kir<br />
        </td>
        <td>
          Kirghiz<br />
          Kyrgyz<br />
        </td>
        <td>
          <a href="models/kirghiz_8_2_2.fst.gz">models/kirghiz_8_2_2.fst.gz</a>(4.3)<br />
        </td>
        <td>
          <a href="Kirghiz/Kirghiz_Cyrillic_wikipedia_symboltable.html">Kirghiz/Kirghiz_Cyrillic_wikipedia_symboltable.html</a><br />
          <a href="Kirghiz/Kirghiz_Turkish_wikipedia_symboltable.html">Kirghiz/Kirghiz_Turkish_wikipedia_symboltable.html</a><br />
          <a href="Kirghiz/Kirghiz_Arabic_wikipedia_symboltable.html">Kirghiz/Kirghiz_Arabic_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="Kirghiz/Kirghiz_swadesh_list.html">Kirghiz/Kirghiz_swadesh_list.html</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/kir">http://phoible.org/languages/kir</a><br />
          <a href="https://en.wikipedia.org/wiki/Kyrgyz_alphabets">https://en.wikipedia.org/wiki/Kyrgyz_alphabets</a><br />
          <a href="https://en.wikipedia.org/wiki/Turkic_languages">https://en.wikipedia.org/wiki/Turkic_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          kon<br />
          kg<br />
        </td>
        <td>
          Kongo<br />
        </td>
        <td>
          <a href="models/kongo_2_4_4.fst.gz">models/kongo_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Kongo/Kongo_wikipedia_symboltable.html">Kongo/Kongo_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://kg.wikipedia.org">http://kg.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/1571">http://phoible.org/inventories/view/1571</a><br />
          <a href="https://en.wikipedia.org/wiki/Kongo_language">https://en.wikipedia.org/wiki/Kongo_language</a><br />
        </td>
      </tr>
      <tr>
        <td>
          kor<br />
          ko<br />
        </td>
        <td>
          Korean<br />
        </td>
        <td>
          <a href="models/korean_2_4_4.fst.gz">models/korean_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Korean/Korean_wikipedia_symboltable.html">Korean/Korean_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/korean.html">sbs-pages/20150418/korean.html</a><br />
          <a href="Korean/Korean_swadesh_list.html">Korean/Korean_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/ko/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/ko/</a><br />
          <a href="http://ko.wikipedia.org">http://ko.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/kor">http://phoible.org/languages/kor</a><br />
          <a href="http://en.wikipedia.org/wiki/Korean_language">http://en.wikipedia.org/wiki/Korean_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/korean?language=ko">http://www.sbs.com.au/yourlanguage/korean?language=ko</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Korean_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Korean_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          kur<br />
          ku<br />
        </td>
        <td>
          Kurdish<br />
        </td>
        <td>
          <a href="models/kurdish_8_2_2.fst.gz">models/kurdish_8_2_2.fst.gz</a>(10.5)<br />
        </td>
        <td>
          <a href="Kurdish/Kurdish_wikipedia_symboltable.html">Kurdish/Kurdish_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/kurdish.html">sbs-pages/20150418/kurdish.html</a><br />
          <a href="Kurdish/Kurdish_swadesh_list.html">Kurdish/Kurdish_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/ku/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/ku/</a><br />
          <a href="http://ku.wikipedia.org">http://ku.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/kmr">http://phoible.org/languages/kmr</a><br />
          <a href="http://en.wikipedia.org/wiki/Kurdish_language">http://en.wikipedia.org/wiki/Kurdish_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/kurdish/">http://www.sbs.com.au/yourlanguage/kurdish/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Kurdish_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Kurdish_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          lao<br />
          lo<br />
        </td>
        <td>
          Lao<br />
        </td>
        <td>
          <a href="models/lao_2_2_2.fst.gz">models/lao_2_2_2.fst.gz</a>(13.9)<br />
        </td>
        <td>
          <a href="Lao/Lao_wikipedia_symboltable.html">Lao/Lao_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/lao.html">sbs-pages/20150418/lao.html</a><br />
          <a href="Lao/Lao_swadesh_list.html">Lao/Lao_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/lo/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/lo/</a><br />
          <a href="http://lo.wikipedia.org">http://lo.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/lao">http://phoible.org/languages/lao</a><br />
          <a href="http://en.wikipedia.org/wiki/Lao_language">http://en.wikipedia.org/wiki/Lao_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/lao/">http://www.sbs.com.au/yourlanguage/lao/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Tai-Kadai_languages">http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Tai-Kadai_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          lav<br />
          lv<br />
        </td>
        <td>
          Latvian<br />
        </td>
        <td>
          <a href="models/latvian_2_4_4.fst.gz">models/latvian_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Latvian/Latvian_wikipedia_symboltable.html">Latvian/Latvian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/latvian.html">sbs-pages/20150418/latvian.html</a><br />
          <a href="Latvian/Latvian_swadesh_list.html">Latvian/Latvian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/lv/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/lv/</a><br />
          <a href="http://lv.wikipedia.org">http://lv.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://en.wikipedia.org/wiki/Latvian_language">http://en.wikipedia.org/wiki/Latvian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/latvian/">http://www.sbs.com.au/yourlanguage/latvian/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Latvian_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Latvian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          lit<br />
          lt<br />
        </td>
        <td>
          Lithuanian<br />
        </td>
        <td>
          <a href="models/lithuanian_4_2_2.fst.gz">models/lithuanian_4_2_2.fst.gz</a>(10.7)<br />
        </td>
        <td>
          <a href="Lithuanian/Lithuanian_wikipedia_symboltable.html">Lithuanian/Lithuanian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/lithuanian.html">sbs-pages/20150418/lithuanian.html</a><br />
          <a href="Lithuanian/Lithuanian_swadesh_list.html">Lithuanian/Lithuanian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/lt/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/lt/</a><br />
          <a href="http://lt.wikipedia.org">http://lt.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/lit">http://phoible.org/languages/lit</a><br />
          <a href="http://en.wikipedia.org/wiki/Lithuanian_language">http://en.wikipedia.org/wiki/Lithuanian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/lithuanian/">http://www.sbs.com.au/yourlanguage/lithuanian/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Lithuanian_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Lithuanian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          lua<br />
        </td>
        <td>
          Luba-Lulua<br />
        </td>
        <td>
          <a href="models/luba-lulua_2_4_4.fst.gz">models/luba-lulua_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Luba-Lulua/Luba-Lulua_wikipedia_symboltable.html">Luba-Lulua/Luba-Lulua_wikipedia_symboltable.html</a><br />
        </td>
        <td>
        </td>
        <td>
          <a href="https://en.wikipedia.org/wiki/Luba-Kasai_language">https://en.wikipedia.org/wiki/Luba-Kasai_language</a><br />
        </td>
      </tr>
      <tr>
        <td>
          luo<br />
        </td>
        <td>
          Luo<br />
          Dholuo<br />
        </td>
        <td>
          <a href="models/luo_4_2_2.fst.gz">models/luo_4_2_2.fst.gz</a>(14.8)<br />
        </td>
        <td>
          <a href="Luo/Luo_wikipedia_symboltable.html">Luo/Luo_wikipedia_symboltable.html</a><br />
        </td>
        <td>
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/448">http://phoible.org/inventories/view/448</a><br />
          <a href="http://phoible.org/inventories/view/694">http://phoible.org/inventories/view/694</a><br />
          <a href="http://phoible.org/inventories/view/153">http://phoible.org/inventories/view/153</a><br />
          <a href="https://en.wikipedia.org/wiki/Luo_dialect">https://en.wikipedia.org/wiki/Luo_dialect</a><br />
        </td>
      </tr>
      <tr>
        <td>
          mal<br />
          ml<br />
        </td>
        <td>
          Malayalam<br />
        </td>
        <td>
          <a href="models/malayalam_4_4_4.fst.gz">models/malayalam_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Malayalam/Malayalam_wikipedia_symboltable.html">Malayalam/Malayalam_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/malayalam.html">sbs-pages/20150418/malayalam.html</a><br />
          <a href="Malayalam/Malayalam_swadesh_list.html">Malayalam/Malayalam_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/ml/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/ml/</a><br />
          <a href="http://ml.wikipedia.org">http://ml.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/mal">http://phoible.org/languages/mal</a><br />
          <a href="http://en.wikipedia.org/wiki/Malayalam_language">http://en.wikipedia.org/wiki/Malayalam_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/malayalam?language=ml">http://www.sbs.com.au/yourlanguage/malayalam?language=ml</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Dravidian_languages">http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Dravidian_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          mar<br />
          mr<br />
        </td>
        <td>
          Marathi<br />
        </td>
        <td>
          <a href="models/marathi_2_3_2.fst.gz">models/marathi_2_3_2.fst.gz</a>(9.4)<br />
        </td>
        <td>
          <a href="Marathi/Marathi_Balbodh_wikipedia_symboltable.html">Marathi/Marathi_Balbodh_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://mr.wikipedia.org">http://mr.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/1766">http://phoible.org/inventories/view/1766</a><br />
          <a href="https://en.wikipedia.org/wiki/Balbodh">https://en.wikipedia.org/wiki/Balbodh</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Indo-Aryan_Swadesh_lists">https://en.wiktionary.org/wiki/Appendix:Indo-Aryan_Swadesh_lists</a><br />
        </td>
      </tr>
      <tr>
        <td>
          mkd<br />
          mk<br />
        </td>
        <td>
          Macedonian<br />
        </td>
        <td>
          <a href="models/macedonian_2_4_4.fst.gz">models/macedonian_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Macedonian/Macedonian_wikipedia_symboltable.html">Macedonian/Macedonian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/macedonian.html">sbs-pages/20150418/macedonian.html</a><br />
          <a href="Macedonian/Macedonian_swadesh_list.html">Macedonian/Macedonian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/mk/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/mk/</a><br />
          <a href="http://mk.wikipedia.org">http://mk.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/mkd">http://phoible.org/languages/mkd</a><br />
          <a href="http://en.wikipedia.org/wiki/Macedonian_language">http://en.wikipedia.org/wiki/Macedonian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/macedonian/">http://www.sbs.com.au/yourlanguage/macedonian/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Macedonian_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Macedonian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          mlg<br />
          mg<br />
        </td>
        <td>
          Malagasy<br />
        </td>
        <td>
          <a href="models/malagasy_2_4_4.fst.gz">models/malagasy_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Malagasy/Malagasy_wikipedia_symboltable.html">Malagasy/Malagasy_wikipedia_symboltable.html</a><br />
        </td>
        <td>
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/31">http://phoible.org/inventories/view/31</a><br />
          <a href="https://en.wikipedia.org/wiki/Malagasy_language">https://en.wikipedia.org/wiki/Malagasy_language</a><br />
        </td>
      </tr>
      <tr>
        <td>
          mlt<br />
          mt<br />
        </td>
        <td>
          Maltese<br />
        </td>
        <td>
          <a href="models/maltese_2_4_4.fst.gz">models/maltese_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Maltese/Maltese_wikipedia_symboltable.html">Maltese/Maltese_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/maltese.html">sbs-pages/20150418/maltese.html</a><br />
          <a href="Maltese/Maltese_swadesh_list.html">Maltese/Maltese_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/mt/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/mt/</a><br />
          <a href="http://mt.wikipedia.org">http://mt.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/mlt">http://phoible.org/languages/mlt</a><br />
          <a href="http://en.wikipedia.org/wiki/Maltese_language">http://en.wikipedia.org/wiki/Maltese_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/maltese/">http://www.sbs.com.au/yourlanguage/maltese/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Maltese_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Maltese_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          mnk<br />
        </td>
        <td>
          Mandinka<br />
        </td>
        <td>
          <a href="models/mandinka_2_4_4.fst.gz">models/mandinka_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Mandinka/Mandinka_wikipedia_symboltable.html">Mandinka/Mandinka_wikipedia_symboltable.html</a><br />
        </td>
        <td>
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/1126">http://phoible.org/inventories/view/1126</a><br />
          <a href="https://en.wikipedia.org/wiki/Mandinka_language">https://en.wikipedia.org/wiki/Mandinka_language</a><br />
        </td>
      </tr>
      <tr>
        <td>
          mon<br />
          mn<br />
        </td>
        <td>
          Mongolian<br />
        </td>
        <td>
          <a href="models/mongolian_4_2_4.fst.gz">models/mongolian_4_2_4.fst.gz</a>(5.5)<br />
        </td>
        <td>
          <a href="Mongolian/Mongolian_wikipedia_symboltable.html">Mongolian/Mongolian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://mn.wikipedia.org">http://mn.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/191">http://phoible.org/inventories/view/191</a><br />
          <a href="https://en.wikipedia.org/wiki/Mongolian_writing_systems">https://en.wikipedia.org/wiki/Mongolian_writing_systems</a><br />
        </td>
      </tr>
      <tr>
        <td>
          mri<br />
          mi<br />
        </td>
        <td>
          Maori<br />
        </td>
        <td>
          <a href="models/maori_2_4_4.fst.gz">models/maori_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Maori/Maori_wikipedia_symboltable.html">Maori/Maori_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="Maori/text_sbs_20150418.html">Maori/text_sbs_20150418.html</a><br />
          <a href="http://mi.wikipedia.org">http://mi.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/42">http://phoible.org/inventories/view/42</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/maori/">http://www.sbs.com.au/yourlanguage/maori/</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Austronesian_Swadesh_lists">https://en.wiktionary.org/wiki/Appendix:Austronesian_Swadesh_lists</a><br />
        </td>
      </tr>
      <tr>
        <td>
          mya<br />
          my<br />
        </td>
        <td>
          Burmese<br />
          Myanmar<br />
        </td>
        <td>
          <a href="models/burmese_4_4_4.fst.gz">models/burmese_4_4_4.fst.gz</a>(37.5)<br />
        </td>
        <td>
          <a href="Burmese/Burmese_wikipedia_symboltable.html">Burmese/Burmese_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/burmese.html">sbs-pages/20150418/burmese.html</a><br />
          <a href="Burmese/Burmese_swadesh_list.html">Burmese/Burmese_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/my/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/my/</a><br />
          <a href="http://my.wikipedia.org">http://my.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/mya">http://phoible.org/languages/mya</a><br />
          <a href="http://en.wikipedia.org/wiki/Burmese_language">http://en.wikipedia.org/wiki/Burmese_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/burmese/">http://www.sbs.com.au/yourlanguage/burmese/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Burmese_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Burmese_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          nan<br />
        </td>
        <td>
          Min-Nan<br />
          Hokkien<br />
        </td>
        <td>
          <a href="models/min-nan_4_4_3.fst.gz">models/min-nan_4_4_3.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Min-Nan/Min-Nan_Hokkien_symboltable.html">Min-Nan/Min-Nan_Hokkien_symboltable.html</a><br />
          <a href="Min-Nan/Min-Nan-Chinese_pronunciations.html">Min-Nan/Min-Nan-Chinese_pronunciations.html</a><br />
        </td>
        <td>
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/481">http://phoible.org/inventories/view/481</a><br />
          <a href="https://repository.ntu.edu.sg/handle/10356/50847">https://repository.ntu.edu.sg/handle/10356/50847</a><br />
          <a href="https://en.wikipedia.org/wiki/Hokkien">https://en.wikipedia.org/wiki/Hokkien</a><br />
        </td>
      </tr>
      <tr>
        <td>
          nde<br />
          nd<br />
        </td>
        <td>
          Ndebele<br />
        </td>
        <td>
          <a href="models/ndebele_2_4_4.fst.gz">models/ndebele_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Ndebele/Ndebele_wikipedia_symboltable.html">Ndebele/Ndebele_wikipedia_symboltable.html</a><br />
        </td>
        <td>
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/1491">http://phoible.org/inventories/view/1491</a><br />
          <a href="https://en.wikipedia.org/wiki/Zimbabwean_Ndebele_language">https://en.wikipedia.org/wiki/Zimbabwean_Ndebele_language</a><br />
          <a href="https://archive.org/details/rosettaproject_nde_vertext-1">https://archive.org/details/rosettaproject_nde_vertext-1</a><br />
        </td>
      </tr>
      <tr>
        <td>
          nep<br />
          ne<br />
        </td>
        <td>
          Nepali<br />
        </td>
        <td>
          <a href="models/nepali_2_4_4.fst.gz">models/nepali_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Nepali/Nepali_wikipedia_symboltable.html">Nepali/Nepali_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/nepali.html">sbs-pages/20150418/nepali.html</a><br />
          <a href="Nepali/Nepali_swadesh_list.html">Nepali/Nepali_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/ne/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/ne/</a><br />
          <a href="http://ne.wikipedia.org">http://ne.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/nep">http://phoible.org/languages/nep</a><br />
          <a href="http://en.wikipedia.org/wiki/Nepali_language">http://en.wikipedia.org/wiki/Nepali_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/nepali?language=ne">http://www.sbs.com.au/yourlanguage/nepali?language=ne</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Indo-Aryan_Swadesh_lists">https://en.wiktionary.org/wiki/Appendix:Indo-Aryan_Swadesh_lists</a><br />
        </td>
      </tr>
      <tr>
        <td>
          nld<br />
          nl<br />
        </td>
        <td>
          Dutch<br />
        </td>
        <td>
          <a href="http://isle.illinois.edu/speech_web_lg/data/g2ps/models/dutch.fst">http://isle.illinois.edu/speech_web_lg/data/g2ps/models/dutch.fst</a>
        </td>
        <td>
          <a href="Dutch/Dutch_wikipedia_symboltable.html">Dutch/Dutch_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/dutch.html">sbs-pages/20150418/dutch.html</a><br />
          <a href="Dutch/Dutch_swadesh_list.html">Dutch/Dutch_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/nl/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/nl/</a><br />
          <a href="http://nl.wikipedia.org">http://nl.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/nld">http://phoible.org/languages/nld</a><br />
          <a href="http://en.wikipedia.org/wiki/Dutch_language">http://en.wikipedia.org/wiki/Dutch_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/dutch/">http://www.sbs.com.au/yourlanguage/dutch/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Dutch_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Dutch_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          nob<br />
          no<br />
        </td>
        <td>
          Norwegian<br />
        </td>
        <td>
          <a href="models/norwegian_2_4_4.fst.gz">models/norwegian_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Norwegian/Norwegian_wikipedia_symboltable.html">Norwegian/Norwegian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/norwegian.html">sbs-pages/20150418/norwegian.html</a><br />
          <a href="Norwegian/Norwegian_swadesh_list.html">Norwegian/Norwegian_swadesh_list.html</a><br />
          <a href="http://no.wikipedia.org">http://no.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/nob">http://phoible.org/languages/nob</a><br />
          <a href="http://en.wikipedia.org/wiki/Norwegian_language">http://en.wikipedia.org/wiki/Norwegian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/norwegian/">http://www.sbs.com.au/yourlanguage/norwegian/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Germanic_languages">http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Germanic_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          nya<br />
          ny<br />
        </td>
        <td>
          Nyanja<br />
          Chewa<br />
        </td>
        <td>
          <a href="models/nyanja_4_4_4.fst.gz">models/nyanja_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Nyanja/Nyanja_wikipedia_symboltable.html">Nyanja/Nyanja_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://ny.wikipedia.org">http://ny.wikipedia.org</a><br />
        </td>
        <td>
          <a href="https://en.wikipedia.org/wiki/Chewa_language">https://en.wikipedia.org/wiki/Chewa_language</a><br />
        </td>
      </tr>
      <tr>
        <td>
          orm<br />
          om<br />
        </td>
        <td>
          Oromo<br />
        </td>
        <td>
          <a href="models/oromo_2_4_4.fst.gz">models/oromo_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Oromo/Oromo_wikipedia_symboltable.html">Oromo/Oromo_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://om.wikipedia.org">http://om.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/1362">http://phoible.org/inventories/view/1362</a><br />
          <a href="https://en.wikipedia.org/wiki/Oromo_language">https://en.wikipedia.org/wiki/Oromo_language</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Afro-Asiatic_Swadesh_lists">https://en.wiktionary.org/wiki/Appendix:Afro-Asiatic_Swadesh_lists</a><br />
        </td>
      </tr>
      <tr>
        <td>
          oss<br />
          os<br />
        </td>
        <td>
          Ossetian<br />
        </td>
        <td>
          <a href="models/ossetian_2_2_4.fst.gz">models/ossetian_2_2_4.fst.gz</a>(8.9)<br />
        </td>
        <td>
          <a href="Ossetian/Ossetian_wikipedia_symboltable.html">Ossetian/Ossetian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://os.wikipedia.org">http://os.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/976">http://phoible.org/inventories/view/976</a><br />
          <a href="https://en.wikipedia.org/wiki/Ossetian_language">https://en.wikipedia.org/wiki/Ossetian_language</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Ossetian_Swadesh_list">https://en.wiktionary.org/wiki/Appendix:Ossetian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          pan<br />
          pa<br />
        </td>
        <td>
          Panjabi<br />
          Punjabi<br />
        </td>
        <td>
          <a href="models/panjabi_4_4_4.fst.gz">models/panjabi_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Panjabi/Panjabi_wikipedia_symboltable.html">Panjabi/Panjabi_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/punjabi.html">sbs-pages/20150418/punjabi.html</a><br />
          <a href="Panjabi/Panjabi_swadesh_list.html">Panjabi/Panjabi_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/pa/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/pa/</a><br />
          <a href="http://pa.wikipedia.org">http://pa.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/pan">http://phoible.org/languages/pan</a><br />
          <a href="http://en.wikipedia.org/wiki/Punjabi_language">http://en.wikipedia.org/wiki/Punjabi_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/punjabi/">http://www.sbs.com.au/yourlanguage/punjabi/</a><br />
        </td>
      </tr>
      <tr>
        <td>
          pap<br />
        </td>
        <td>
          Papiamento<br />
        </td>
        <td>
          <a href="models/papiamento_4_4_4.fst.gz">models/papiamento_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Papiamento/Papiamento_wikipedia_symboltable.html">Papiamento/Papiamento_wikipedia_symboltable.html</a><br />
        </td>
        <td>
        </td>
        <td>
          <a href="https://en.wikipedia.org/wiki/Papiamento">https://en.wikipedia.org/wiki/Papiamento</a><br />
        </td>
      </tr>
      <tr>
        <td>
          pes<br />
          fa<br />
        </td>
        <td>
          Iranian_Persian<br />
        </td>
        <td>
          <a href="models/persian_2_2_2.fst.gz">models/persian_2_2_2.fst.gz</a>(0.5)<br />
        </td>
        <td>
          <a href="Persian/Persian_wikipedia_symboltable.html">Persian/Persian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/persian-farsi.html">sbs-pages/20150418/persian-farsi.html</a><br />
          <a href="Persian/Persian_swadesh_list.html">Persian/Persian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/fa/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/fa/</a><br />
          <a href="http://fa.wikipedia.org">http://fa.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/pes">http://phoible.org/languages/pes</a><br />
          <a href="http://en.wikipedia.org/wiki/Persian_language">http://en.wikipedia.org/wiki/Persian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/persian-farsi/">http://www.sbs.com.au/yourlanguage/persian-farsi/</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Indo-Iranian_Swadesh_lists">https://en.wiktionary.org/wiki/Appendix:Indo-Iranian_Swadesh_lists</a><br />
        </td>
      </tr>
      <tr>
        <td>
          pol<br />
          pl<br />
        </td>
        <td>
          Polish<br />
        </td>
        <td>
          <a href="models/polish_2_2_2.fst.gz">models/polish_2_2_2.fst.gz</a>(35.2)<br />
        </td>
        <td>
          <a href="Polish/Polish_wikipedia_symboltable.html">Polish/Polish_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/polish.html">sbs-pages/20150418/polish.html</a><br />
          <a href="Polish/Polish_swadesh_list.html">Polish/Polish_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/pl/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/pl/</a><br />
          <a href="http://pl.wikipedia.org">http://pl.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/pol">http://phoible.org/languages/pol</a><br />
          <a href="http://en.wikipedia.org/wiki/Polish_language">http://en.wikipedia.org/wiki/Polish_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/polish/">http://www.sbs.com.au/yourlanguage/polish/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Polish_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Polish_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          por<br />
          pt<br />
        </td>
        <td>
          Portuguese<br />
        </td>
        <td>
          <a href="http://isle.illinois.edu/speech_web_lg/data/g2ps/models/portuguese.fst">http://isle.illinois.edu/speech_web_lg/data/g2ps/models/portuguese.fst</a>
        </td>
        <td>
          <a href="Portuguese/Portuguese_wikipedia_symboltable.html">Portuguese/Portuguese_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/portuguese.html">sbs-pages/20150418/portuguese.html</a><br />
          <a href="Portuguese/Portuguese_swadesh_list.html">Portuguese/Portuguese_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/pt/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/pt/</a><br />
          <a href="http://pt.wikipedia.org">http://pt.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/por">http://phoible.org/languages/por</a><br />
          <a href="http://en.wikipedia.org/wiki/Portuguese_language">http://en.wikipedia.org/wiki/Portuguese_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/portuguese/">http://www.sbs.com.au/yourlanguage/portuguese/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Portuguese_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Portuguese_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          prs<br />
          fa<br />
        </td>
        <td>
          Dari<br />
        </td>
        <td>
          <a href="models/dari_2_4_4.fst.gz">models/dari_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Dari/Dari_wikipedia_symboltable.html">Dari/Dari_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/dari.html">sbs-pages/20150418/dari.html</a><br />
          <a href="Dari/Dari_swadesh_list.html">Dari/Dari_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/fa/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/fa/</a><br />
          <a href="http://fa.wikipedia.org">http://fa.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://en.wikipedia.org/wiki/Dari_language">http://en.wikipedia.org/wiki/Dari_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/dari/">http://www.sbs.com.au/yourlanguage/dari/</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Indo-Aryan_Swadesh_lists">https://en.wiktionary.org/wiki/Appendix:Indo-Aryan_Swadesh_lists</a><br />
        </td>
      </tr>
      <tr>
        <td>
          pus<br />
          ps<br />
        </td>
        <td>
          Pushto<br />
          Pashto<br />
        </td>
        <td>
          <a href="models/pushto_8_3_2.fst.gz">models/pushto_8_3_2.fst.gz</a>(16.0)<br />
        </td>
        <td>
          <a href="Pushto/Pushto_wikipedia_symboltable.html">Pushto/Pushto_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/pashto.html">sbs-pages/20150418/pashto.html</a><br />
          <a href="Pushto/Pushto_swadesh_list.html">Pushto/Pushto_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/ps/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/ps/</a><br />
          <a href="http://ps.wikipedia.org">http://ps.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/pst">http://phoible.org/languages/pst</a><br />
          <a href="http://en.wikipedia.org/wiki/Pashto_language">http://en.wikipedia.org/wiki/Pashto_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/pashto/">http://www.sbs.com.au/yourlanguage/pashto/</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Indo-Iranian_Swadesh_lists">https://en.wiktionary.org/wiki/Appendix:Indo-Iranian_Swadesh_lists</a><br />
        </td>
      </tr>
      <tr>
        <td>
          que<br />
          qu<br />
        </td>
        <td>
          Quechua<br />
        </td>
        <td>
          <a href="models/quechua_4_4_4.fst.gz">models/quechua_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Quechua/Quechua_wikipedia_symboltable.html">Quechua/Quechua_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://qu.wikipedia.org">http://qu.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/2024">http://phoible.org/inventories/view/2024</a><br />
          <a href="https://en.wikipedia.org/wiki/Quechuan_languages">https://en.wikipedia.org/wiki/Quechuan_languages</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Quechuan_Swadesh_list">https://en.wiktionary.org/wiki/Appendix:Quechuan_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          rar<br />
        </td>
        <td>
          Rarotongan<br />
          Cook Islands Maori<br />
        </td>
        <td>
          <a href="models/rarotongan_2_4_4.fst.gz">models/rarotongan_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Rarotongan/Rarotongan_wikipedia_symboltable.html">Rarotongan/Rarotongan_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="Rarotongan/text_sbs_20150418.html">Rarotongan/text_sbs_20150418.html</a><br />
          <a href="Rarotongan/Rarotongan_swadesh_list.html">Rarotongan/Rarotongan_swadesh_list.html</a><br />
        </td>
        <td>
          <a href="http://en.wikipedia.org/wiki/Cook_Islands_Maori">http://en.wikipedia.org/wiki/Cook_Islands_Maori</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/cookislands-maori/">http://www.sbs.com.au/yourlanguage/cookislands-maori/</a><br />
        </td>
      </tr>
      <tr>
        <td>
          rhg<br />
        </td>
        <td>
          Rohingya<br />
        </td>
        <td>
          <a href="models/rohingya_2_4_4.fst.gz">models/rohingya_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Rohingya/Rohingya_wikipedia_symboltable.html">Rohingya/Rohingya_wikipedia_symboltable.html</a><br />
        </td>
        <td>
        </td>
        <td>
          <a href="https://en.wikipedia.org/wiki/Rohingya_language">https://en.wikipedia.org/wiki/Rohingya_language</a><br />
        </td>
      </tr>
      <tr>
        <td>
          ron<br />
          ro<br />
        </td>
        <td>
          Romanian<br />
        </td>
        <td>
          <a href="models/romanian_2_3_3.fst.gz">models/romanian_2_3_3.fst.gz</a>(0.2)<br />
        </td>
        <td>
          <a href="Romanian/Romanian_wikipedia_symboltable.html">Romanian/Romanian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/romanian.html">sbs-pages/20150418/romanian.html</a><br />
          <a href="Romanian/Romanian_swadesh_list.html">Romanian/Romanian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/ro/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/ro/</a><br />
          <a href="http://ro.wikipedia.org">http://ro.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/ron">http://phoible.org/languages/ron</a><br />
          <a href="http://en.wikipedia.org/wiki/Romanian_language">http://en.wikipedia.org/wiki/Romanian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/romanian/">http://www.sbs.com.au/yourlanguage/romanian/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Romanian_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Romanian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          run<br />
          rn<br />
        </td>
        <td>
          Rundi<br />
          Kirundi<br />
        </td>
        <td>
          <a href="models/rundi_2_4_4.fst.gz">models/rundi_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Rundi/Rundi_wikipedia_symboltable.html">Rundi/Rundi_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://rn.wikipedia.org/">http://rn.wikipedia.org/</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/run">http://phoible.org/languages/run</a><br />
          <a href="https://en.wikipedia.org/wiki/Kirundi">https://en.wikipedia.org/wiki/Kirundi</a><br />
        </td>
      </tr>
      <tr>
        <td>
          rus<br />
          ru<br />
        </td>
        <td>
          Russian<br />
        </td>
        <td>
          <a href="http://isle.illinois.edu/speech_web_lg/data/g2ps/models/russian.fst">http://isle.illinois.edu/speech_web_lg/data/g2ps/models/russian.fst</a>
        </td>
        <td>
          <a href="Russian/Russian_wikipedia_symboltable.html">Russian/Russian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/russian.html">sbs-pages/20150418/russian.html</a><br />
          <a href="Russian/Russian_swadesh_list.html">Russian/Russian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/ru/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/ru/</a><br />
          <a href="http://ru.wikipedia.org">http://ru.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/rus">http://phoible.org/languages/rus</a><br />
          <a href="http://en.wikipedia.org/wiki/Russian_language">http://en.wikipedia.org/wiki/Russian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/russian/">http://www.sbs.com.au/yourlanguage/russian/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Russian_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Russian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          sin<br />
          si<br />
        </td>
        <td>
          Sinhala<br />
        </td>
        <td>
          <a href="models/sinhala_2_4_4.fst.gz">models/sinhala_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Sinhala/Sinhala_wikipedia_symboltable.html">Sinhala/Sinhala_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/sinhalese.html">sbs-pages/20150418/sinhalese.html</a><br />
          <a href="Sinhala/Sinhala_swadesh_list.html">Sinhala/Sinhala_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/si/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/si/</a><br />
          <a href="http://si.wikipedia.org">http://si.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/sin">http://phoible.org/languages/sin</a><br />
          <a href="http://en.wikipedia.org/wiki/Sinhala_language">http://en.wikipedia.org/wiki/Sinhala_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/sinhalese?language=si">http://www.sbs.com.au/yourlanguage/sinhalese?language=si</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Sinhalese_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Sinhalese_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          slk<br />
          sk<br />
        </td>
        <td>
          Slovak<br />
        </td>
        <td>
          <a href="models/slovak_4_4_4.fst.gz">models/slovak_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Slovak/Slovak_wikipedia_symboltable.html">Slovak/Slovak_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/slovak.html">sbs-pages/20150418/slovak.html</a><br />
          <a href="Slovak/Slovak_swadesh_list.html">Slovak/Slovak_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/sk/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/sk/</a><br />
          <a href="http://sk.wikipedia.org">http://sk.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://en.wikipedia.org/wiki/Slovak_language">http://en.wikipedia.org/wiki/Slovak_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/slovak/">http://www.sbs.com.au/yourlanguage/slovak/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Slovak_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Slovak_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          slv<br />
          sl<br />
        </td>
        <td>
          Slovenian<br />
        </td>
        <td>
          <a href="models/slovenian_2_4_4.fst.gz">models/slovenian_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Slovenian/Slovenian_wikipedia_symboltable.html">Slovenian/Slovenian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/slovenian.html">sbs-pages/20150418/slovenian.html</a><br />
          <a href="Slovenian/Slovenian_swadesh_list.html">Slovenian/Slovenian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/sl/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/sl/</a><br />
          <a href="http://sl.wikipedia.org">http://sl.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/slv">http://phoible.org/languages/slv</a><br />
          <a href="http://en.wikipedia.org/wiki/Slovene_language">http://en.wikipedia.org/wiki/Slovene_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/slovenian/">http://www.sbs.com.au/yourlanguage/slovenian/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Slovene_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Slovene_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          smo<br />
          sm<br />
        </td>
        <td>
          Samoan<br />
        </td>
        <td>
          <a href="models/samoan_2_4_4.fst.gz">models/samoan_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Samoan/Samoan_wikipedia_symboltable.html">Samoan/Samoan_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/samoan.html">sbs-pages/20150418/samoan.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/sm/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/sm/</a><br />
          <a href="http://sm.wikipedia.org">http://sm.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://en.wikipedia.org/wiki/Samoan_language">http://en.wikipedia.org/wiki/Samoan_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/samoan?language=sm">http://www.sbs.com.au/yourlanguage/samoan?language=sm</a><br />
        </td>
      </tr>
      <tr>
        <td>
          sna<br />
          sn<br />
        </td>
        <td>
          Shona<br />
        </td>
        <td>
          <a href="models/shona_4_4_4.fst.gz">models/shona_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Shona/Shona_wikipedia_symboltable.html">Shona/Shona_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://sn.wikipedia.org">http://sn.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/sna">http://phoible.org/languages/sna</a><br />
          <a href="http://en.wikipedia.org/wiki/Shona_language">http://en.wikipedia.org/wiki/Shona_language</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Bantu_Swadesh_lists">https://en.wiktionary.org/wiki/Appendix:Bantu_Swadesh_lists</a><br />
        </td>
      </tr>
      <tr>
        <td>
          som<br />
          so<br />
        </td>
        <td>
          Somali<br />
        </td>
        <td>
          <a href="models/somali_2_4_4.fst.gz">models/somali_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Somali/Somali_wikipedia_symboltable.html">Somali/Somali_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/somali.html">sbs-pages/20150418/somali.html</a><br />
          <a href="Somali/Somali_swadesh_list.html">Somali/Somali_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/so/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/so/</a><br />
          <a href="http://so.wikipedia.org">http://so.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/som">http://phoible.org/languages/som</a><br />
          <a href="http://en.wikipedia.org/wiki/Somali_language">http://en.wikipedia.org/wiki/Somali_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/somali/">http://www.sbs.com.au/yourlanguage/somali/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Afro-Asiatic_languages">http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Afro-Asiatic_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          sot<br />
          st<br />
        </td>
        <td>
          Sotho<br />
        </td>
        <td>
          <a href="models/sotho_4_4_4.fst.gz">models/sotho_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Sotho/Sotho_wikipedia_symboltable.html">Sotho/Sotho_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://st.wikipedia.org">http://st.wikipedia.org</a><br />
        </td>
        <td>
          <a href="https://en.wikipedia.org/wiki/Sotho_orthography">https://en.wikipedia.org/wiki/Sotho_orthography</a><br />
        </td>
      </tr>
      <tr>
        <td>
          spa<br />
          es<br />
        </td>
        <td>
          Spanish<br />
        </td>
        <td>
          <a href="http://isle.illinois.edu/speech_web_lg/data/g2ps/models/spanish.fst">http://isle.illinois.edu/speech_web_lg/data/g2ps/models/spanish.fst</a>
        </td>
        <td>
          <a href="Spanish/Spanish_wikipedia_symboltable.html">Spanish/Spanish_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/spanish.html">sbs-pages/20150418/spanish.html</a><br />
          <a href="Spanish/Spanish_swadesh_list.html">Spanish/Spanish_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/es/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/es/</a><br />
          <a href="http://es.wikipedia.org">http://es.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/spa">http://phoible.org/languages/spa</a><br />
          <a href="http://en.wikipedia.org/wiki/Spanish_language">http://en.wikipedia.org/wiki/Spanish_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/spanish/">http://www.sbs.com.au/yourlanguage/spanish/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Spanish_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Spanish_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          sqi<br />
          sq<br />
        </td>
        <td>
          Albanian<br />
        </td>
        <td>
          <a href="models/albanian_2_4_4.fst.gz">models/albanian_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Albanian/Albanian_wikipedia_symboltable.html">Albanian/Albanian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/albanian.html">sbs-pages/20150418/albanian.html</a><br />
          <a href="Albanian/Albanian_swadesh_list.html">Albanian/Albanian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/sq/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/sq/</a><br />
          <a href="http://sq.wikipedia.org">http://sq.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/als">http://phoible.org/languages/als</a><br />
          <a href="http://en.wikipedia.org/wiki/Albanian_language">http://en.wikipedia.org/wiki/Albanian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/albanian">http://www.sbs.com.au/yourlanguage/albanian</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Albanian_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Albanian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          srp<br />
          sr<br />
        </td>
        <td>
          Serbian<br />
        </td>
        <td>
          <a href="models/serbian_2_4_4.fst.gz">models/serbian_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Serbian/Serbian_wikipedia_symboltable.html">Serbian/Serbian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/serbian.html">sbs-pages/20150418/serbian.html</a><br />
          <a href="Serbian/Serbian_swadesh_list.html">Serbian/Serbian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/sr/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/sr/</a><br />
          <a href="http://sr.wikipedia.org">http://sr.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://en.wikipedia.org/wiki/Serbian_language">http://en.wikipedia.org/wiki/Serbian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/serbian/">http://www.sbs.com.au/yourlanguage/serbian/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Serbo-Croatian_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Serbo-Croatian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          sun<br />
          su<br />
        </td>
        <td>
          Sundanese<br />
        </td>
        <td>
          <a href="models/sundanese_2_4_4.fst.gz">models/sundanese_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Sundanese/Sundanese_wikipedia_symboltable.html">Sundanese/Sundanese_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://su.wikipedia.org">http://su.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/35">http://phoible.org/inventories/view/35</a><br />
          <a href="https://en.wikipedia.org/wiki/Sundanese_alphabet">https://en.wikipedia.org/wiki/Sundanese_alphabet</a><br />
        </td>
      </tr>
      <tr>
        <td>
          swe<br />
          sv<br />
        </td>
        <td>
          Swedish<br />
        </td>
        <td>
          <a href="models/swedish_4_4_4.fst.gz">models/swedish_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Swedish/Swedish_wikipedia_symboltable.html">Swedish/Swedish_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/swedish.html">sbs-pages/20150418/swedish.html</a><br />
          <a href="Swedish/Swedish_swadesh_list.html">Swedish/Swedish_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/sv/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/sv/</a><br />
          <a href="http://sv.wikipedia.org">http://sv.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/swe">http://phoible.org/languages/swe</a><br />
          <a href="http://en.wikipedia.org/wiki/Swedish_language">http://en.wikipedia.org/wiki/Swedish_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/swedish/">http://www.sbs.com.au/yourlanguage/swedish/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Swedish_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Swedish_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          swh<br />
          sw<br />
        </td>
        <td>
          Swahili<br />
        </td>
        <td>
          <a href="models/swahili_4_2_2.fst.gz">models/swahili_4_2_2.fst.gz</a>(11.4)<br />
        </td>
        <td>
          <a href="Swahili/Swahili_wikipedia_symboltable.html">Swahili/Swahili_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/swahili.html">sbs-pages/20150418/swahili.html</a><br />
          <a href="Swahili/Swahili_swadesh_list.html">Swahili/Swahili_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/sw/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/sw/</a><br />
          <a href="http://sw.wikipedia.org">http://sw.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/swh">http://phoible.org/languages/swh</a><br />
          <a href="http://en.wikipedia.org/wiki/Swahili_language">http://en.wikipedia.org/wiki/Swahili_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/swahili/">http://www.sbs.com.au/yourlanguage/swahili/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Swahili_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Swahili_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          tam<br />
          ta<br />
        </td>
        <td>
          Tamil<br />
        </td>
        <td>
          <a href="models/tamil_2_3_3.fst.gz">models/tamil_2_3_3.fst.gz</a>(3.6)<br />
        </td>
        <td>
          <a href="Tamil/Tamil_wikipedia_symboltable.html">Tamil/Tamil_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/tamil.html">sbs-pages/20150418/tamil.html</a><br />
          <a href="Tamil/Tamil_swadesh_list.html">Tamil/Tamil_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/ta/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/ta/</a><br />
          <a href="http://ta.wikipedia.org">http://ta.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/tam">http://phoible.org/languages/tam</a><br />
          <a href="http://en.wikipedia.org/wiki/Tamil_language">http://en.wikipedia.org/wiki/Tamil_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/tamil?language=ta">http://www.sbs.com.au/yourlanguage/tamil?language=ta</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Dravidian_languages">http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Dravidian_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          tat<br />
          tt<br />
        </td>
        <td>
          Tatar<br />
        </td>
        <td>
          <a href="models/tatar_2_2_2.fst.gz">models/tatar_2_2_2.fst.gz</a>(0.6)<br />
        </td>
        <td>
          <a href="Tatar/Tatar_wikipedia_symboltable.html">Tatar/Tatar_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="Tatar/Tatar_swadesh_list.html">Tatar/Tatar_swadesh_list.html</a><br />
          <a href="http://tt.wikipedia.org">http://tt.wikipedia.org</a><br />
        </td>
        <td>
          <a href="https://en.wikipedia.org/wiki/Tatar_alphabet">https://en.wikipedia.org/wiki/Tatar_alphabet</a><br />
          <a href="https://en.wikipedia.org/wiki/Turkic_languages">https://en.wikipedia.org/wiki/Turkic_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          tel<br />
          te<br />
        </td>
        <td>
          Telugu<br />
        </td>
        <td>
          <a href="models/telugu_4_4_4.fst.gz">models/telugu_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Telugu/Telugu_wikipedia_symboltable.html">Telugu/Telugu_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://te.wikipedia.org">http://te.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/8">http://phoible.org/inventories/view/8</a><br />
          <a href="https://en.wikipedia.org/wiki/Telugu_script">https://en.wikipedia.org/wiki/Telugu_script</a><br />
        </td>
      </tr>
      <tr>
        <td>
          tgk<br />
          tg<br />
        </td>
        <td>
          Tajik<br />
        </td>
        <td>
          <a href="models/tajik_2_2_2.fst.gz">models/tajik_2_2_2.fst.gz</a>(0.8)<br />
        </td>
        <td>
          <a href="Tajik/Tajik_wikipedia_symboltable.html">Tajik/Tajik_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://tg.wikipedia.org">http://tg.wikipedia.org</a><br />
        </td>
        <td>
          <a href="https://en.wikipedia.org/wiki/Tajik_alphabet">https://en.wikipedia.org/wiki/Tajik_alphabet</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Tajik_Swadesh_list">https://en.wiktionary.org/wiki/Appendix:Tajik_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          tgl<br />
          tl<br />
        </td>
        <td>
          Tagalog<br />
        </td>
        <td>
          <a href="models/tagalog_4_2_3.fst.gz">models/tagalog_4_2_3.fst.gz</a>(17.5)<br />
        </td>
        <td>
          <a href="Tagalog/Tagalog_wikipedia_symboltable.html">Tagalog/Tagalog_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/fijian.html">sbs-pages/20150418/fijian.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/fj/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/fj/</a><br />
          <a href="http://tl.wikipedia.org">http://tl.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/tgl">http://phoible.org/languages/tgl</a><br />
          <a href="https://en.wikipedia.org/wiki/Tagalog_language">https://en.wikipedia.org/wiki/Tagalog_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/fijian/">http://www.sbs.com.au/yourlanguage/fijian/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Tagalog_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Tagalog_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          tha<br />
          th<br />
        </td>
        <td>
          Thai<br />
        </td>
        <td>
          <a href="models/thai_4_4_4.fst.gz">models/thai_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Thai/Thai_wikipedia_symboltable.html">Thai/Thai_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/thai.html">sbs-pages/20150418/thai.html</a><br />
          <a href="Thai/Thai_swadesh_list.html">Thai/Thai_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/th/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/th/</a><br />
          <a href="http://th.wikipedia.org">http://th.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/tha">http://phoible.org/languages/tha</a><br />
          <a href="http://en.wikipedia.org/wiki/Thai_language">http://en.wikipedia.org/wiki/Thai_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/thai/">http://www.sbs.com.au/yourlanguage/thai/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Thai_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Thai_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          tir<br />
          ti<br />
        </td>
        <td>
          Tigrinya<br />
        </td>
        <td>
          <a href="models/tigrinya_2_4_4.fst.gz">models/tigrinya_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Tigrinya/Tigrinya_wikipedia_symboltable.html">Tigrinya/Tigrinya_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/tigrinya.html">sbs-pages/20150418/tigrinya.html</a><br />
          <a href="Tigrinya/Tigrinya_swadesh_list.html">Tigrinya/Tigrinya_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/ti/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/ti/</a><br />
          <a href="http://ti.wikipedia.org">http://ti.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/tir">http://phoible.org/languages/tir</a><br />
          <a href="http://en.wikipedia.org/wiki/Tigrinya_language">http://en.wikipedia.org/wiki/Tigrinya_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/tigrinya/">http://www.sbs.com.au/yourlanguage/tigrinya/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Afro-Asiatic_languages">http://en.wiktionary.org/wiki/Appendix:Swadesh_lists_for_Afro-Asiatic_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          ton<br />
          to<br />
        </td>
        <td>
          Tonga<br />
        </td>
        <td>
          <a href="models/tonga_2_4_4.fst.gz">models/tonga_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Tonga/Tonga_wikipedia_symboltable.html">Tonga/Tonga_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/tongan.html">sbs-pages/20150418/tongan.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/to/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/to/</a><br />
          <a href="http://to.wikipedia.org">http://to.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/ton">http://phoible.org/languages/ton</a><br />
          <a href="http://en.wikipedia.org/wiki/Tongan_language">http://en.wikipedia.org/wiki/Tongan_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/tongan/">http://www.sbs.com.au/yourlanguage/tongan/</a><br />
        </td>
      </tr>
      <tr>
        <td>
          tpi<br />
        </td>
        <td>
          Tok Pisin<br />
        </td>
        <td>
          <a href="models/tok-pisin_8_3_2.fst.gz">models/tok-pisin_8_3_2.fst.gz</a>(16.4)<br />
        </td>
        <td>
          <a href="Tok-Pisin/Tok-Pisin_wikipedia_symboltable.html">Tok-Pisin/Tok-Pisin_wikipedia_symboltable.html</a><br />
        </td>
        <td>
        </td>
        <td>
          <a href="http://phoible.org/languages/tpi">http://phoible.org/languages/tpi</a><br />
          <a href="https://en.wikipedia.org/wiki/Tok_Pisin">https://en.wikipedia.org/wiki/Tok_Pisin</a><br />
        </td>
      </tr>
      <tr>
        <td>
          tuk<br />
        </td>
        <td>
          Turkmen<br />
        </td>
        <td>
          <a href="models/turkmen_2_2_2.fst.gz">models/turkmen_2_2_2.fst.gz</a>(0.2)<br />
        </td>
        <td>
          <a href="Turkmen/Turkmen_Cyrillic_wikipedia_symboltable.html">Turkmen/Turkmen_Cyrillic_wikipedia_symboltable.html</a><br />
          <a href="Turkmen/Turkmen_Turkish_wikipedia_symboltable.html">Turkmen/Turkmen_Turkish_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="Turkmen/Turkmen_swadesh_list.html">Turkmen/Turkmen_swadesh_list.html</a><br />
        </td>
        <td>
          <a href="http://en.wikipedia.org/wiki/Turkmen_language">http://en.wikipedia.org/wiki/Turkmen_language</a><br />
          <a href="https://en.wikipedia.org/wiki/Turkic_languages">https://en.wikipedia.org/wiki/Turkic_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          tur<br />
          tr<br />
        </td>
        <td>
          Turkish<br />
        </td>
        <td>
          <a href="http://isle.illinois.edu/speech_web_lg/data/g2ps/models/turkish.fst">http://isle.illinois.edu/speech_web_lg/data/g2ps/models/turkish.fst</a>
        </td>
        <td>
          <a href="Turkish/Turkish_wikipedia_symboltable.html">Turkish/Turkish_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/turkish.html">sbs-pages/20150418/turkish.html</a><br />
          <a href="Turkish/Turkish_swadesh_list.html">Turkish/Turkish_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/tr/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/tr/</a><br />
          <a href="http://tr.wikipedia.org">http://tr.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/tur">http://phoible.org/languages/tur</a><br />
          <a href="http://en.wikipedia.org/wiki/Turkish_language">http://en.wikipedia.org/wiki/Turkish_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/turkish/">http://www.sbs.com.au/yourlanguage/turkish/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Turkish_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Turkish_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          uig<br />
        </td>
        <td>
          Uighur<br />
          Uyghur<br />
        </td>
        <td>
          <a href="models/uighur_2_3_2.fst.gz">models/uighur_2_3_2.fst.gz</a>(74.5)<br />
        </td>
        <td>
          <a href="Uighur/Uighur_Arabic_wikipedia_symboltable.html">Uighur/Uighur_Arabic_wikipedia_symboltable.html</a><br />
          <a href="Uighur/Uighur_Cyrillic_wikipedia_symboltable.html">Uighur/Uighur_Cyrillic_wikipedia_symboltable.html</a><br />
          <a href="Uighur/Uighur_Latin_wikipedia_symboltable.html">Uighur/Uighur_Latin_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="Uighur/Uighur_swadesh_list.html">Uighur/Uighur_swadesh_list.html</a><br />
        </td>
        <td>
          <a href="http://en.wikipedia.org/wiki/Uyghur_language">http://en.wikipedia.org/wiki/Uyghur_language</a><br />
          <a href="https://en.wikipedia.org/wiki/Turkic_languages">https://en.wikipedia.org/wiki/Turkic_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          ukr<br />
          uk<br />
        </td>
        <td>
          Ukrainian<br />
        </td>
        <td>
          <a href="models/ukrainian_4_4_4.fst.gz">models/ukrainian_4_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Ukrainian/Ukrainian_wikipedia_symboltable.html">Ukrainian/Ukrainian_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/ukrainian.html">sbs-pages/20150418/ukrainian.html</a><br />
          <a href="Ukrainian/Ukrainian_swadesh_list.html">Ukrainian/Ukrainian_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/uk/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/uk/</a><br />
          <a href="http://uk.wikipedia.org">http://uk.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/ukr">http://phoible.org/languages/ukr</a><br />
          <a href="http://en.wikipedia.org/wiki/Ukrainian_language">http://en.wikipedia.org/wiki/Ukrainian_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/ukrainian/">http://www.sbs.com.au/yourlanguage/ukrainian/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Ukrainian_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Ukrainian_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          urd<br />
          ur<br />
        </td>
        <td>
          Urdu<br />
        </td>
        <td>
          <a href="models/urdu_2_4_4.fst.gz">models/urdu_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Urdu/Urdu_wikipedia_symboltable.html">Urdu/Urdu_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/urdu.html">sbs-pages/20150418/urdu.html</a><br />
          <a href="Urdu/Urdu_swadesh_list.html">Urdu/Urdu_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/ur/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/ur/</a><br />
          <a href="http://ur.wikipedia.org">http://ur.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/urd">http://phoible.org/languages/urd</a><br />
          <a href="http://en.wikipedia.org/wiki/Urdu_language">http://en.wikipedia.org/wiki/Urdu_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/urdu?language=ur">http://www.sbs.com.au/yourlanguage/urdu?language=ur</a><br />
        </td>
      </tr>
      <tr>
        <td>
          uzb<br />
        </td>
        <td>
          Uzbek<br />
        </td>
        <td>
          <a href="models/uzbek_2_2_2.fst.gz">models/uzbek_2_2_2.fst.gz</a>(1.4)<br />
        </td>
        <td>
          <a href="Uzbek/Uzbek_Cyrillic_wikipedia_symboltable.html">Uzbek/Uzbek_Cyrillic_wikipedia_symboltable.html</a><br />
          <a href="Uzbek/Uzbek_Latin_wikipedia_symboltable.html">Uzbek/Uzbek_Latin_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="Uzbek/Uzbek_swadesh_list.html">Uzbek/Uzbek_swadesh_list.html</a><br />
        </td>
        <td>
          <a href="http://en.wikipedia.org/wiki/Uzbek_language">http://en.wikipedia.org/wiki/Uzbek_language</a><br />
          <a href="https://en.wikipedia.org/wiki/Turkic_languages">https://en.wikipedia.org/wiki/Turkic_languages</a><br />
        </td>
      </tr>
      <tr>
        <td>
          vie<br />
          vi<br />
        </td>
        <td>
          Vietnamese<br />
        </td>
        <td>
          <a href="models/vietnamese_2_2_2.fst.gz">models/vietnamese_2_2_2.fst.gz</a>(24.8)<br />
        </td>
        <td>
          <a href="Vietnamese/Vietnamese_wikipedia_symboltable.html">Vietnamese/Vietnamese_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/vietnamese.html">sbs-pages/20150418/vietnamese.html</a><br />
          <a href="Vietnamese/Vietnamese_swadesh_list.html">Vietnamese/Vietnamese_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/vi/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/vi/</a><br />
          <a href="http://vi.wikipedia.org">http://vi.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/vie">http://phoible.org/languages/vie</a><br />
          <a href="http://en.wikipedia.org/wiki/Vietnamese_language">http://en.wikipedia.org/wiki/Vietnamese_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/vietnamese?language=vi">http://www.sbs.com.au/yourlanguage/vietnamese?language=vi</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Vietnamese_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Vietnamese_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          wol<br />
          wo<br />
        </td>
        <td>
          Wolof<br />
        </td>
        <td>
          <a href="models/wolof_2_4_4.fst.gz">models/wolof_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Wolof/Wolof_wikipedia_symboltable.html">Wolof/Wolof_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://wo.wikipedia.org">http://wo.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/wol">http://phoible.org/languages/wol</a><br />
          <a href="http://en.wikipedia.org/wiki/Wolof_language">http://en.wikipedia.org/wiki/Wolof_language</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Niger-Congo_Swadesh_lists">https://en.wiktionary.org/wiki/Appendix:Niger-Congo_Swadesh_lists</a><br />
        </td>
      </tr>
      <tr>
        <td>
          wuu<br />
        </td>
        <td>
          Wu_Chinese<br />
        </td>
        <td>
          <a href="models/wu_2_2_3.fst.gz">models/wu_2_2_3.fst.gz</a>(90.4)<br />
        </td>
        <td>
          <a href="Wu_Chinese/Wu_Chinese_pronunciations.html">Wu_Chinese/Wu_Chinese_pronunciations.html</a><br />
        </td>
        <td>
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/17">http://phoible.org/inventories/view/17</a><br />
          <a href="https://en.wikipedia.org/wiki/Wu_Chinese">https://en.wikipedia.org/wiki/Wu_Chinese</a><br />
        </td>
      </tr>
      <tr>
        <td>
          xho<br />
          xh<br />
        </td>
        <td>
          Xhosa<br />
        </td>
        <td>
          <a href="models/xhosa_2_4_4.fst.gz">models/xhosa_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Xhosa/Xhosa_wikipedia_symboltable.html">Xhosa/Xhosa_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://xh.wikipedia.org">http://xh.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/inventories/view/1319">http://phoible.org/inventories/view/1319</a><br />
          <a href="https://en.wikipedia.org/wiki/Xhosa_language">https://en.wikipedia.org/wiki/Xhosa_language</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Bantu_Swadesh_lists">https://en.wiktionary.org/wiki/Appendix:Bantu_Swadesh_lists</a><br />
        </td>
      </tr>
      <tr>
        <td>
          yor<br />
        </td>
        <td>
          Yoruba<br />
        </td>
        <td>
          <a href="models/yoruba_2_3_2.fst.gz">models/yoruba_2_3_2.fst.gz</a>(0.8)<br />
        </td>
        <td>
          <a href="Yoruba/Yoruba_wikipedia_symboltable.html">Yoruba/Yoruba_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://yo.wikipedia.org">http://yo.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/yor">http://phoible.org/languages/yor</a><br />
          <a href="http://en.wikipedia.org/wiki/Yoruba_language">http://en.wikipedia.org/wiki/Yoruba_language</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Niger-Congo_Swadesh_lists">https://en.wiktionary.org/wiki/Appendix:Niger-Congo_Swadesh_lists</a><br />
        </td>
      </tr>
      <tr>
        <td>
          yue<br />
        </td>
        <td>
          Yue_Chinese<br />
          Cantonese<br />
        </td>
        <td>
          <a href="models/yue_2_2_4.fst.gz">models/yue_2_2_4.fst.gz</a>(15.6)<br />
        </td>
        <td>
          <a href="Yue_Chinese/Yue_Chinese_Jyutping_wikipedia_symboltable.html">Yue_Chinese/Yue_Chinese_Jyutping_wikipedia_symboltable.html</a><br />
          <a href="Yue_Chinese/Yue_Chinese_YaleCantonese_wikipedia_symboltable.html">Yue_Chinese/Yue_Chinese_YaleCantonese_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/cantonese.html">sbs-pages/20150418/cantonese.html</a><br />
          <a href="Yue_Chinese/Yue_Chinese_swadesh_list.html">Yue_Chinese/Yue_Chinese_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/zh-yue/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/zh-yue/</a><br />
          <a href="http://zh-yue.wikipedia.org">http://zh-yue.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/yue">http://phoible.org/languages/yue</a><br />
          <a href="http://en.wikipedia.org/wiki/Yue_Chinese">http://en.wikipedia.org/wiki/Yue_Chinese</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/cantonese?language=zh-hant">http://www.sbs.com.au/yourlanguage/cantonese?language=zh-hant</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Cantonese_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Cantonese_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          zsm<br />
          ms<br />
        </td>
        <td>
          Standard_Malay<br />
        </td>
        <td>
          <a href="models/malay_2_4_4.fst.gz">models/malay_2_4_4.fst.gz</a>(N/A)<br />
        </td>
        <td>
          <a href="Standard_Malay/Standard_Malay_wikipedia_symboltable.html">Standard_Malay/Standard_Malay_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="sbs-pages/20150418/malay.html">sbs-pages/20150418/malay.html</a><br />
          <a href="Standard_Malay/Standard_Malay_swadesh_list.html">Standard_Malay/Standard_Malay_swadesh_list.html</a><br />
          <a href="http://ifp-08.ifp.uiuc.edu/public/wikipedia/ms/">http://ifp-08.ifp.uiuc.edu/public/wikipedia/ms/</a><br />
          <a href="http://ms.wikipedia.org">http://ms.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/zsm">http://phoible.org/languages/zsm</a><br />
          <a href="http://en.wikipedia.org/wiki/Malay_language">http://en.wikipedia.org/wiki/Malay_language</a><br />
          <a href="http://www.sbs.com.au/yourlanguage/malay/">http://www.sbs.com.au/yourlanguage/malay/</a><br />
          <a href="http://en.wiktionary.org/wiki/Appendix:Malay_Swadesh_list">http://en.wiktionary.org/wiki/Appendix:Malay_Swadesh_list</a><br />
        </td>
      </tr>
      <tr>
        <td>
          zul<br />
          zu<br />
        </td>
        <td>
          Zulu<br />
        </td>
        <td>
          <a href="models/zulu_4_4_3.fst.gz">models/zulu_4_4_3.fst.gz</a>(10.2)<br />
        </td>
        <td>
          <a href="Zulu/Zulu_wikipedia_symboltable.html">Zulu/Zulu_wikipedia_symboltable.html</a><br />
        </td>
        <td>
          <a href="http://zu.wikipedia.org">http://zu.wikipedia.org</a><br />
        </td>
        <td>
          <a href="http://phoible.org/languages/zul">http://phoible.org/languages/zul</a><br />
          <a href="http://en.wikipedia.org/wiki/Zulu_language">http://en.wikipedia.org/wiki/Zulu_language</a><br />
          <a href="https://en.wiktionary.org/wiki/Appendix:Zulu_Swadesh_list">https://en.wiktionary.org/wiki/Appendix:Zulu_Swadesh_list</a><br />
        </td>
      </tr>
    </table>

