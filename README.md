# nnrv_bible
Nepali Bible in javascript format
Verses with red color are wrapped inside <Red></Red>


Filename Identification according to bible Chapters:
  GEN.json - Genesis - उत्‍पत्ति
  EXO.json - Exodus - प्रस्‍थान
  LEV.json - Leviticus - लेवीहरू
  NUM.json - Numbers - गन्ती
  DEU.json - Deuteronomy - व्यवस्था
  JOS.json - Joshua - यहोशू
  JDG.json - Judges - न्यायकर्ताहरू
  RUT.json - Ruth - रूथ
  1SA.json - 1 Samuel - १ शमूएल
  2SA.json - 2 Samuel - २ शमूएल
  1KI.json - 1 Kings - १ राजाहरू
  2Ki.json - 2 Kings - २ राजाहरू
  1CH.json - 1 Chronicles - १ इतिहास
  2CH.json - 2 Chronicles - २ इतिहास
  EZR.json - Ezra - एज्रा
  NEH.json - Nehemiah - नहेम्‍याह
  EST.json - Esther - एस्‍तर
  JOB.json - Job - अय्‍यूब
  PSA.json - Psalms - भजनसंग्रह
  PRO.json - Proverbs - हितोपदेश
  ECC.json - Ecclesiastes - उपदेशक
  SNG.json - Song of songs - श्रेष्‍ठगीत
  ISA.json - Isaiah - यशैया
  JER.json - Jeremiah - यर्मिया
  LAM.json - Lamentations - विलाप
  EZK.json - Ezekiel - इजकिएल
  DAN.json - Daniel - दानिएल
  HOS.json - Hosea - होशे
  JOL.json - Joel - योएल
  AMO.json - Amos - आमोस
  OBA.json - Obadiah - ओबदिया
  JON.json - Jonah - योना
  MIC.json - Micah - मीका
  NAM.json - Nahum - नहूम
  HAB.json - HabakkuK - हबकूक
  ZEP.json - Zephaniah - सपन्‍याह
  HAG.json - Haggai - हाग्‍गै
  ZEC.json - Zechariah - जकरिया
  MAL.json - Malachi - मलाकी
  MAT.json - Matthew - मत्ती
  MRK.json - Mark - मर्कूस
  LUK.json - Luke - लूका
  JHN.json - John - यूहन्‍ना
  ACT.json - Acts - प्रेरित
  ROM.json - Romans - रोमी
  1CO.json - 1 Corinthians - १ कोरिन्थी
  2CO.json - 2 Corinthians - २ कोरिन्थी
  GAL.json - Galatians - गलाती
  EPH.json - Ephesians - एफिसी
  PHP.json - Philippians - फिलिप्पी
  COL.json - Colossians - कलस्सी
  1TH.json - 1 Thessalonians - १ थेसलोनिकी
  2TH.json - 2 Thessalonians - २ थेसलोनिकी
  1TI.json - 1 Timothy - १ तिमोथी
  2TI.json - 2 Timothy - २ तिमोथी
  TIT.json - Titus - तीतस
  PHM.json - Philemon - फिलेमोन
  HEB.json - Hebrews - हिब्रू
  JAS.json - James - याकूब
  1PE.json - 1 Peter - १ पत्रुस
  2PE.json - 2 Peter - २ पत्रुस
  1JN.json - 1 John - १ यूहन्‍ना
  2JN.json - 2 John - २ यूहन्‍ना
  3JN.json - 3 John - ३ यूहन्‍ना
  JUD.json - Jude -‍ यहूदा
  REV.json - Revelation - प्रकाश

You can use similar structure below to navigate to specific chapters with their chapter names:
[
    {"filename": "GEN.json", "englishName": "Genesis", "nepaliName": "उत्‍पत्ति"},
    {"filename": "EXO.json", "englishName": "Exodus", "nepaliName": "प्रस्‍थान"},
    {"filename": "LEV.json", "englishName": "Leviticus", "nepaliName": "लेवीहरू"},
    {"filename": "NUM.json", "englishName": "Numbers", "nepaliName": "गन्ती"},
    {"filename": "DEU.json", "englishName": "Deuteronomy", "nepaliName": "व्यवस्था"},
    {"filename": "JOS.json", "englishName": "Joshua", "nepaliName": "यहोशू"},
    {"filename": "JDG.json", "englishName": "Judges", "nepaliName": "न्यायकर्ताहरू"},
    {"filename": "RUT.json", "englishName": "Ruth", "nepaliName": "रूथ"},
    {"filename": "1SA.json", "englishName": "1 Samuel", "nepaliName": "१ शमूएल"},
    {"filename": "2SA.json", "englishName": "2 Samuel", "nepaliName": "२ शमूएल"},
    {"filename": "1KI.json", "englishName": "1 Kings", "nepaliName": "१ राजाहरू"},
    {"filename": "2KI.json", "englishName": "2 Kings", "nepaliName": "२ राजाहरू"},
    {"filename": "1CH.json", "englishName": "1 Chronicles", "nepaliName": "१ इतिहास"},
    {"filename": "2CH.json", "englishName": "2 Chronicles", "nepaliName": "२ इतिहास"},
    {"filename": "EZR.json", "englishName": "Ezra", "nepaliName": "एज्रा"},
    {"filename": "NEH.json", "englishName": "Nehemiah", "nepaliName": "नहेम्‍याह"},
    {"filename": "EST.json", "englishName": "Esther", "nepaliName": "एस्‍तर"},
    {"filename": "JOB.json", "englishName": "Job", "nepaliName": "अय्‍यूब"},
    {"filename": "PSA.json", "englishName": "Psalms", "nepaliName": "भजनसंग्रह"},
    {"filename": "PRO.json", "englishName": "Proverbs", "nepaliName": "हितोपदेश"},
    {"filename": "ECC.json", "englishName": "Ecclesiastes", "nepaliName": "उपदेशक"},
    {"filename": "SNG.json", "englishName": "Song of songs", "nepaliName": "श्रेष्‍ठगीत"},
    {"filename": "ISA.json", "englishName": "Isaiah", "nepaliName": "यशैया"},
    {"filename": "JER.json", "englishName": "Jeremiah", "nepaliName": "यर्मिया"},
    {"filename": "LAM.json", "englishName": "Lamentations", "nepaliName": "विलाप"},
    {"filename": "EZK.json", "englishName": "Ezekiel", "nepaliName": "इजकिएल"},
    {"filename": "DAN.json", "englishName": "Daniel", "nepaliName": "दानिएल"},
    {"filename": "HOS.json", "englishName": "Hosea", "nepaliName": "होशे"},
    {"filename": "JOL.json", "englishName": "Joel", "nepaliName": "योएल"},
    {"filename": "AMO.json", "englishName": "Amos", "nepaliName": "आमोस"},
    {"filename": "OBA.json", "englishName": "Obadiah", "nepaliName": "ओबदिया"},
    {"filename": "JON.json", "englishName": "Jonah", "nepaliName": "योना"},
    {"filename": "MIC.json", "englishName": "Micah", "nepaliName": "मीका"},
    {"filename": "NAM.json", "englishName": "Nahum", "nepaliName": "नहूम"},
    {"filename": "HAB.json", "englishName": "Habakkuk", "nepaliName": "हबकूक"},
    {"filename": "ZEP.json", "englishName": "Zephaniah", "nepaliName": "सपन्‍याह"},
    {"filename": "HAG.json", "englishName": "Haggai", "nepaliName": "हाग्‍गै"},
    {"filename": "ZEC.json", "englishName": "Zechariah", "nepaliName": "जकरिया"},
    {"filename": "MAL.json", "englishName": "Malachi", "nepaliName": "मलाकी"},
    {"filename": "MAT.json", "englishName": "Matthew", "nepaliName": "मत्ती"},
    {"filename": "MRK.json", "englishName": "Mark", "nepaliName": "मर्कूस"},
    {"filename": "LUK.json", "englishName": "Luke", "nepaliName": "लूका"},
    {"filename": "JHN.json", "englishName": "John", "nepaliName": "यूहन्‍ना"},
    {"filename": "ACT.json", "englishName": "Acts", "nepaliName": "प्रेरित"},
    {"filename": "ROM.json", "englishName": "Romans", "nepaliName": "रोमी"},
    {"filename": "1CO.json", "englishName": "1 Corinthians", "nepaliName": "१ कोरिन्थी"},
    {"filename": "2CO.json", "englishName": "2 Corinthians", "nepaliName": "२ कोरिन्थी"},
    {"filename": "GAL.json", "englishName": "Galatians", "nepaliName": "गलाती"},
    {"filename": "EPH.json", "englishName": "Ephesians", "nepaliName": "एफिसी"},
    {"filename": "PHP.json", "englishName": "Philippians", "nepaliName": "फिलिप्पी"},
    {"filename": "COL.json", "englishName": "Colossians", "nepaliName": "कलस्सी"},
    {"filename": "1TH.json", "englishName": "1 Thessalonians", "nepaliName": "१ थेसलोनिकी"},
    {"filename": "2TH.json", "englishName": "2 Thessalonians", "nepaliName": "२ थेसलोनिकी"},
    {"filename": "1TI.json", "englishName": "1 Timothy", "nepaliName": "१ तिमोथी"},
    {"filename": "2TI.json", "englishName": "2 Timothy", "nepaliName": "२ तिमोथी"},
    {"filename": "TIT.json", "englishName": "Titus", "nepaliName": "तीतस"},
    {"filename": "PHM.json", "englishName": "Philemon", "nepaliName": "फिलेमोन"},
    {"filename": "HEB.json", "englishName": "Hebrews", "nepaliName": "हिब्रू"},
    {"filename": "JAS.json", "englishName": "James", "nepaliName": "याकूब"},
    {"filename": "1PE.json", "englishName": "1 Peter", "nepaliName": "१ पत्रुस"},
    {"filename": "2PE.json", "englishName": "2 Peter", "nepaliName": "२ पत्रुस"},
    {"filename": "1JN.json", "englishName": "1 John", "nepaliName": "१ यूहन्‍ना"},
    {"filename": "2JN.json", "englishName": "2 John", "nepaliName": "२ यूहन्‍ना"},
    {"filename": "3JN.json", "englishName": "3 John", "nepaliName": "३ यूहन्‍ना"},
    {"filename": "JUD.json", "englishName": "Jude", "nepaliName": "यहूदा"},
    {"filename": "REV.json", "englishName": "Revelation", "nepaliName": "प्रकाश"}
  ]


Feel free to use them.
