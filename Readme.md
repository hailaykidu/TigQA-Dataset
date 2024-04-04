### TigQA: Question Answering in Low Resource Scenarios: Expert Annotated Dataset for Tigrinya Language

### Abstract
The absence of explicitly tailored, accessible annotated datasets for educational purposes presents a notable obsta-
cle for NLP tasks in languages with limited resources. This study initially explores the feasibility of using machine
translation (MT) to convert an existing dataset into a Tigrinya dataset in SQuAD format. As a result, we present
TIGQA, an expert-annotated dataset containing 2,685 question-answer pairs covering 122 diverse topics such as
climate, water, and traﬀic. These pairs are from 537 context paragraphs in publicly accessible Tigrinya and Biology
books. Through comprehensive analyses, we demonstrate that the TIGQA dataset requires skills beyond simple
word matching, requiring both single-sentence and multiple-sentence inference abilities. We conduct experiments
using state-of-the-art MRC methods, marking the first exploration of such models on TIGQA. Additionally, we esti-
mate human performance on the dataset and juxtapose it with the results obtained from pre-trained models. The
notable disparities between human performance and the best model performance underscore the potential for fu-
ture enhancements to TIGQA through continued research. Our dataset is freely accessible to
encourage the research community to address the challenges in the Tigrinya MRC.

Keywords: Tigrinya QA dataset, Low resource QA dataset, domain-specific QA

Dataset

   {
  "data": 
  [
    {
      "title": "Context1",
      "paragraphs": [
        {
          "context": "ነባሪ ኣየር ኣብ ሓደ ከባቢ ዝውቱር ዝኾነ ኩነታት አየር እዩ ። እዚ ምስ ስነምድራዊ  ኣቀማምጣ ከባቢ ቀጥታዊ ርክብ ኣለዎ ። እዚ ኩነታት ሓደ ከባቢ ካብ ዝግለፀሎም መዳያት ሓደ እዩ። ነባሪ ኣየር ደጉዓ ፣ ሓውሲ ደጉዓን ቆላን ተባሂሉ ኣብ ሰለስተ ይኽፈል። ሕድ ሕድ ነባሪ ኣየር ናይ ባዕሉ ዝኾነ ብራኸን መጠን ዋዒን ኣለዎ ። ደጉዓ ዝኾኑ ቦታታት ካብ ፀፍሒ ባሕሪ ንላዕሊ ካብ 2,500-4,000 ሜትር ዝኸውን ብራኸ ኣለዎም ።",
          "qas": [
            {
              "question": "ነባሪ ኣየር እንታይ እዩ?",
              "id": "1",
              "answers": [
                {
                  "text": "ኣብ ሓደ ከባቢ ዝውቱር ዝኾነ ኩነታት አየር",
                  "answer_start": 0,
                  "answer_end": 28
                }
              ]
            },
            {
              "question": "ምስ ስነምድራዊ ኣቀማምጣ  ከባቢ ቀጥታዊ ርክብ  ዘለዎ እንታይ እዩ?",
              "id": "2",
              "answers": [
                {
                  "text": "ነባሪ ኣየር",
                  "answer_start": 76,
                  "answer_end": 88
                }
              ]
            },
            {
              "question": "ነባሪ ኣየር ኣብ ክንደይ ይኽፈል?",
              "id": "3",
              "answers": [
                {
                  "text": "ኣብ ሰለስተ",
                  "answer_start": 132,
                  "answer_end": 141
                }
              ]
            },
            {
              "question": "ክፋላት  ነባሪ ኣየር እንታይ እንታይ እየን?",
              "id": "4",
              "answers": [
                {
                  "text": "ደጉዓ፣ሓውሲ ደጉዓን ቆላን",
                  "answer_start": 142,
                  "answer_end": 161
                }
              ]
            },
            {
              "question": "ሕድ ሕድ ነባሪ ኣየር ናይ ባዕሉ እንታይ ኣለዎ?",
              "id": "5",
              "answers": [
                {
                  "text": "ብራኸንመጠንዋዒን",
                  "answer_start": 181,
                  "answer_end": 195
                }
              ]
            }
          ]
        }
      ]
    }
  ],
   

  "data": [
    {
      "title": "Context2",
      "paragraphs": [
        {
          "context": "ደጉዓ ኣዝዩ ቆራርን ኣስሓይታ ዝበዝሖን ኩነታት ኣየር ኣለዎ።እዚ ነባሪ ኣየር ከም ሩዝ ፣ ስርናይ፣ ዓልቋይን ዓረስን ዝበሉ ዘራእቲን ከም ሰሰግን ኣወሱዳን ዝበሉ ቅመማትን ንምፍራይ ምቹው እዩ ። ብተመሳሳሊ ደጉዓ ከም ኣፍራስን ኣባጊዕን ንዝበሉ እንስሳት  ዝሰማማዕ ነባሪ ኣየር እዩ።",
          "qas": [
            {
              "question": "ኣዝዩ ቆራር ኩነታት ኣየር ዘለዎ ኣየናይ ነባሪ ኣየር እዩ?",
              "id": "6",
              "answers": [
                {
                  "text": "ደጉዓ",
                  "answer_start": 9,
                  "answer_end": 13
                }
              ]
            },
            {
              "question": "ደጉዓ እንታይ ዓይነት ኩነታት ኣየር ኣለዎ?",
              "id": "7",
              "answers": [
                {
                  "text": "ኣዝዩ ቆራርን ኣስሓይታ ዝበዝሖ",
                  "answer_start": 15,
                  "answer_end": 30
                }
              ]
            },
            {
              "question": "ደጉዓ ኣየኖት ኣእኻል የብቁል?",
              "id": "8",
              "answers": [
                {
                  "text": "ሩዝ፣ስርናይ፣ዓልቋይን ዓረስን",
                  "answer_start": 45,
                  "answer_end": 65
                }
              ]
            },
            {
              "question": "ደጉዓ ከመይ ዝበሉ ቅመማት ንምፍራይ ይጥዕም?",
              "id": "9",
              "answers": [
                {
                  "text": "ሰሰግን ኣወሱዳን",
                  "answer_start": 90,
                  "answer_end": 101
                }
              ]
            },
            {
              "question": "ደጉዓ ንኸመይ ዝበላ እንስሳት ዘቤት ይሰማማዕ?",
              "id": "10",
              "answers": [
                {
                  "text": "ኣፍራስን ኣባጊዕን",
                  "answer_start": 125,
                  "answer_end": 140
                }
              ]
            }
          ]
        }
      ]
    }
  ],

 
  "data": [
    {
      "title": "Context3",
      "paragraphs": [
        {
          "context": "መጓዓዝያ ማይ ብታንኳ ፣ ብጃልባን ብመርከብን ንዝግበር ጉዕዞ የመልክት ። ብመርከብ ዝግበር ጉዕዞ መብዛሕትኡ እዋን ብዙሕ ንብረትን ሰብን ካብ ሃገር ናብ ሃገር ብዝሓሰረ ዋጋ ንምጉዕዓዝ የገልግል ። ብቕልጣፈ እንትረአ ግና ካብቶም ካልኦት ዝተሓተ እዩ ። መርከብ  200 ሰብ ትፅዕን",
          "qas": [
            {
              "question": "ብታንኳን ብጃልባን ዝግበር ምጉዕዓዝ እንታይ ይበሃል?",
              "id": "11",
              "answers": [
                {
                  "text": "መጓዓዝያ ማይ",
                  "answer_start": 0,
                  "answer_end": 10
                }
              ]
            },
            {
              "question": "ብዙሕ ንብረት ንሰብን ብዝሓሰረ ዋጋ ንምጉዕዓዝ ዘገልግል ብምንታይ ዝግበር ጉዕዞ እዩ?",
              "id": "12",
              "answers": [
                {
                  "text": "ብመርከብ",
                  "answer_start": 30,
                  "answer_end": 35
                }
              ]
            },
            {
              "question": "ብቕልጣፍኡ ዝተሓተ መጓዓዝያ ማይ ኣየናይ እዩ?",
              "id": "13",
              "answers": [
                {
                  "text": "መርከብ",
                  "answer_start": 67,
                  "answer_end": 72
                }
              ]
            },
            {
              "question": "ብዙሕ ንብረትን ሰብን ካብ ሃገር ናብ ሃገር  ዘጓዓዕዝ እንታይ እዩ?",
              "id": "14",
              "answers": [
                {
                  "text": "መርከብ",
                  "answer_start": 98,
                  "answer_end": 103
                }
              ]
            },
            {
              "question": "መርከብ ክንደይ ሰብ ትፅዕን",
              "id": "15",
              "answers": [
                {
                  "text": "200",
                  "answer_start": 135,
                  "answer_end": 138
                }
              ]
            }
          ]
        }
      ]
    }
  ],
  
   "data": [
    {
      "title": "Context4",
      "paragraphs": [
        {
          "context": "መጓዓዝያ ማይ ብታንኳ ፣ ብጃልባን ብመርከብን ንዝግበር ጉዕዞ የመልክት ። ብመርከብ ዝግበር ጉዕዞ መብዛሕትኡ እዋን ብዙሕ ንብረትን ሰብን ካብ ሃገር ናብ ሃገር ብዝሓሰረ ዋጋ ንምጉዕዓዝ የገልግል ። ብቕልጣፈ እንትረአ ግና ካብቶም ካልኦት ዝተሓተ እዩ ። መርከብ  200 ሰብ ትፅዕን",
          "qas": [
            {
              "question": "ብታንኳን ብጃልባን ዝግበር ምጉዕዓዝ እንታይ ይበሃል?",
              "id": "16",
              "answers": [
                {
                  "text": "መጓዓዝያ ማይ",
                  "answer_start": 0,
                  "answer_end": 10
                }
              ]
            },
            {
              "question": "ብዙሕ ንብረት ንሰብን ብዝሓሰረ ዋጋ ንምጉዕዓዝ ዘገልግል ብምንታይ ዝግበር ጉዕዞ እዩ?",
              "id": "17",
              "answers": [
                {
                  "text": "ብመርከብ",
                  "answer_start": 30,
                  "answer_end": 35
                }
              ]
            },
            {
              "question": "ብቕልጣፍኡ ዝተሓተ መጓዓዝያ ማይ ኣየናይ እዩ?",
              "id": "18",
              "answers": [
                {
                  "text": "መርከብ",
                  "answer_start": 67,
                  "answer_end": 72
                }
              ]
            },
            {
              "question": "ብዙሕ ንብረትን ሰብን ካብ ሃገር ናብ ሃገር  ዘጓዓዕዝ እንታይ እዩ?",
              "id": "19",
              "answers": [
                {
                  "text": "መርከብ",
                  "answer_start": 98,
                  "answer_end": 103
                }
              ]
            },
            {
              "question": "መርከብ ክንደይ ሰብ ትፅዕን",
              "id": "20",
              "answers": [
                {
                  "text": "200",
                  "answer_start": 135,
                  "answer_end": 138
                }
              ]
            }
          ]
        }
      ]
    },
    {
      "title": "Context5",
      "paragraphs": [
        {
          "context": "መጓዓዝያ ኣየር  ብሄሊኮፕተር ዝግበር ጉዕዞ እዩ። ኣውሮፕላንን  ካብ ኩሎም ዓይነታት መጓዓዝያ ዝቀልጠፉ እዮም ። ብመኪናን ብመርከብን መዓልቲታትን ሰሙናትን ዝወስድ ጉዕዞ ብነፋሪት ግና ብደቓይቕ ወይ ብሰዓታት ይሽፈን ። እዚ ዓይነት መጓዓዝያ ልዑል ዋጋ ይሓትት ። ብመርከብ ምስ ዝግበር ምጉዕዓዝ ንብረትን ሰብን እንትነፃፀር ግና መጓዓዝያ ኣየር ዝሽከሞ ዓቐን ንብረትን ሰብን ትሑት እዩ ።",
          "qas": [
            {
              "question": "መጓዓዝያ ኣየር ብምንተይ ዝግበር ጉዕዞ እዩ?",
              "id": "21",
              "answers": [
                {
                  "text": "ብሄሊኮፕተር",
                  "answer_start": 10,
                  "answer_end": 20
                }
              ]
            },
            {
              "question": "ካብ ኩሎም ዓይነታት መጓዓዝያ ዝቀልጠፉ ኣየኖት እዮም?",
              "id": "22",
              "answers": [
                {
                  "text": "ኣውሮፕላን",
                  "answer_start": 42,
                  "answer_end": 50
                }
              ]
            },
            {
              "question": "ብመኪናን ብመርከብን መዓልቲታትን ሰሙናትን ዝወስድ፣ ብነፋሪት ክንደይ ይወስድ?",
              "id": "23",
              "answers": [
                {
                  "text": "ደቓይቕ ወይ ሰዓታት",
                  "answer_start": 99,
                  "answer_end": 114
                }
              ]
            },
            {
              "question": "ልዑል ዋጋ ዝሓትት ኣየናይ ዓይነት መጓዓዝያ እዩ?",
              "id": "24",
              "answers": [
                {
                  "text": "ብነፋሪት",
                  "answer_start": 204,
                  "answer_end": 212
                }
              ]
            },
            {
              "question": "መጓዓዝያ ኣየር ዝሽከሞ ዓቐን ንብረትን ሰብን ትሑት እዩ?",
              "id": "25",
              "answers": [
                {
                  "text": "ትሑት",
                  "answer_start": 247,
                  "answer_end": 252
                }
              ]
            }
          ]
        }
      ]
    }
  ],
  
  "data": [
    {
      "title": "Context6",
      "paragraphs": [
        {
          "context": "ኮማንደር ጀማል ፦ ዝኸበርኩም ተምሃሮ ፣ ፈለማ ብዛዕባይ ክነግረኩም ። ስመይ ጀማል መስዑድ ይበሃል ። ኣብ ከተማና ሓላፊ ምክልኻል ሓደጋ ትራፊክ እየ ። እምበኣር ብሕቶ ክጅምር ትራፊክ እንታይ ማለት እዩ ? ተምሃራይ ፦ ኣብ ፅርግያ ደው ኢሉ ንመኻይን ዝቆፃፀር ሰብ እዩ ። ኮማንደር ጀማል ፦ ፅቡቕ ኣነ ፖሊስ ትራፊክ እየ ። ካብ ቦታ ናብ ቦታ ዝግበር ዝኾነ ዓይነት ምንቅስቓስ ትራፊክ ይበሃል ። እቲ ምንቅስቓስ ብሰብ ፣ ብእንስሳት ወይ ድማ ብመሳርሒታት መጓዓዝያ ዝፍፀም ክኸውን ይኽእል ። እቲ ሰብ ንመጓዓዝያ ንዝገብሩዎ ምንቅስቓስ ሕጋዊ ፣ ሰላማዊን ስሉጥን ንክኸውን ዝቆፃፀር ኣካል ድማ ፖሊስ ትራፊክ ይበሃል ።",
          "qas": [
            {
              "question": "ሓላፊ ምክልኻል ሓደጋ ትራፊክ መን ይበሃሉ?",
              "id": "26",
              "answers": [
                {
                  "text": "ጀማል መስዑድ",
                  "answer_start": 77,
                  "answer_end": 88
                }
              ]
            },
            {
              "question": "ሓላፊ ምክልኻል ሓደጋ ትራፊክ ዘረባይ ብምንታይ ክጅምር በሉ?",
              "id": "27",
              "answers": [
                {
                  "text": "ብሕቶ",
                  "answer_start": 132,
                  "answer_end": 138
                }
              ]
            },
            {
              "question": "ሕቶ ኮማንደር ጀማል እንታይ ዝብል ነበረ?",
              "id": "28",
              "answers": [
                {
                  "text": "ትራፊክ እንታይ ማለት እዩ?",
                  "answer_start": 204,
                  "answer_end": 226
                }
              ]
            },
            {
              "question": "ንሕቶ ኮማንደር ጀማል መን መልሲ ሃበ?",
              "id": "29",
              "answers": [
                {
                  "text": "ተመሃራይ",
                  "answer_start": 282,
                  "answer_end": 290
                }
              ]
            },
            {
              "question": "ካብ ቦታ ናብ ቦታ ዝግበር ዝኾነ ዓይነት ምንቅስቓስ እንታይ ይበሃል?",
              "id": "30",
              "answers": [
                {
                  "text": "ትራፊክ",
                  "answer_start": 383,
                  "answer_end": 390
                }
              ]
            }
          ]
        }
      ]
    },
    {
      "title": "Context7",
      "paragraphs": [
        {
          "context": "ተምሃሪት ፦ ኣብ ክልልና ብሰንኪ ሓደጋ ትራፊክ ዘጋጠመ ዕንወት ክሳብ ክንደየናይ እዩ?   ኮማንደር ጀማል ፦ ኣብ ትግራይ በብዓመቱ ብዙሓት ሓደጋታት የጋጥሙ እዮም ። ንኣብነት ናይ ክልተ ዓመታት ንርአ ። ብ2003 ዓ.ም. 858 ወገናትና ሓደጋ ትራፊክ ኣጋጢሙዎም ። ካብ እዚኦም 180 ሞይቶም፤390 ንከቢድ ጉድኣት ኣካል ተቓሊዖም ። እቶም ዝተረፉ 288 ድማ ቀሊል ጉድኣት ኣጋጢሙዎም ። ብ 2004 ዓ.ም.  11,539, 112.00 ብር ዘውፅእ ንብረት ዓንዩ ። ኣብ ህይወት ሰብ እንትንርኢ  834 ወገናትና ሓደጋ ትራፊክ ኣጋጢሙዎም።ካብዚኦም  217  ሞይቶም ፤ 332 ንከቢድ ጉድኣት ኣካል ተሳጢሖም ። ዝተረፉ 282 ድማ ቀሊል ጉድኣት ኣጋጢሙዎም። 22,840,580.00 ብር ዘውፅእ ንብረት ዓንዩ ። ",
          "qas": [
            {
              "question": "ኣብ ክልልና ብሰንኪ ሓደጋ ትራፊክ ዘጋጠመ ዕንወት ክሳብ ክንደየናይ እዩ?ኢሉ ዝሓተተ መን እዩ?",
              "id": "31",
              "answers": [
                {
                  "text": "ተመሃሪት",
                  "answer_start": 0,
                  "answer_end": 8
                }
              ]
            },
            {
              "question": "ናይ ክንደይ ዓመታት ሓደጋ ትራፊክ እዮም ከም ኣብነት ኣቕሪቦም?",
              "id": "32",
              "answers": [
                {
                  "text": "ናይ ክልተዓመታት",
                  "answer_start": 124,
                  "answer_end": 137
                }
              ]
            },
            {
              "question": "858 ወገናትሓደጋ ትራፊክ ዘጋጠሞም መዓስ እዩ?",
              "id": "33",
              "answers": [
                {
                  "text": "ብ2003 ዓ.ም",
                  "answer_start": 199,
                  "answer_end": 210
                }
              ]
            },
            {
              "question": "ሓደጋትራፊክ ካብ  ዘጋጠሞም 834 ወገናት ክንደይ ሞይቶም?",
              "id": "34",
              "answers": [
                {
                  "text": "180",
                  "answer_start": 359,
                  "answer_end": 362
                }
              ]
            },
            {
              "question": "ብ2004 ዓ.ም. ክንደይ ብር ዘውፅእ ንብረት ዓንዩ?",
              "id": "35",
              "answers": [
                {
                  "text": "11,539,112.00 ብር",
                  "answer_start": 422,
                  "answer_end": 438
                }
              ]
            }
          ]
        }
      ]
    },
    {
      "title": "Context8",
      "paragraphs": [
        {
          "context": "ተምሃሪት ፦ ቀንዲ መንቀሊ ሓደጋ ትራፊክ እንታይ እዩ ? ኮማንደር ጀማል ፦መንቀሊኡ ዘወርቲን ኣጋራትን ዝፈጥሩዎ ጌጋ እዩ ። ብወገን ዘወርቲ ፣ ኣጋር ቀዲሙ ንኽሰግር ዘይምግባርን ብናህሪ ምዝዋርን ጐሊሆም ዝረአዩ ፀገማት እዮም ። ሰኺርካ ምዝዋር ፣ መዕጠቖ ዘይምእሳር ፣ ሕጊታት ትራፊክ ዘይምኽባር ዝበሉ ፀገማት እውን መንቀሊታት እዮም ። ብወገን ፣ ናይ ምዕራብ ከም ውሽጥ ዝፈለጠን ሓደ ዝበለጠን ትራፊክ እዮም ። ኣብ ወገን ፣ ኣደንቅን ምምላስ ፣ ስእሊ ዝልባር ንምሕላስ ፣ ስርዓትን ኣድሓኖም ኣብ ኣምንፎኣት ዝበሉ መንቀሊታት እዮም ።",
          "qas": [
            {
              "question": "ቀንዲ መንቀሊ ሓደጋ ትራፊክ እንታይ እዩ?",
              "id": "36",
              "answers": [
                {
                  "text": "ተምሃሪት",
                  "answer_start": 0,
                  "answer_end": 8
                }
              ]
            },
            {
              "question": "መንቀሊኡ ዘወርቲን ኣጋራትን ዝፈጥሩዎ ጌጋ እዮም ዝበለጠን ናይ ስልታነ ትራፊክ እዮም?",
              "id": "37",
              "answers": [
                {
                  "text": "መዕጠቖ ዘይምእሳር",
                  "answer_start": 198,
                  "answer_end": 216
                }
              ]
            },
            {
              "question": "ናይ ምዕራብ ትራፊክ ምምላስ ሓደ ዝበለጠን እዮም?",
              "id": "38",
              "answers": [
                {
                  "text": "ኣደንቅን",
                  "answer_start": 326,
                  "answer_end": 332
                }
              ]
            },
            {
              "question": "ናይ ኣምንፎኣት ትራፊክ ዝበሉ መንቀሊታት እዮም ክንቅሳቐሱ ፀገማት ዝበሉ ኢሉ ዝተረፈሉ መን እዮም?",
              "id": "39",
              "answers": [
                {
                  "text": "ስእሊ ዝልባር",
                  "answer_start": 488,
                  "answer_end": 498
                }
              ]
            }
          ]
        }
      ]
    }
  ],
  
  "data": [
    {
      "title": "Context 39",
      "paragraphs": [
        {
          "context": "እዋኑ ግንቦት ነበረ ሓረስቶት ጣብያ ሓዱሽ ዓለም ቁሸት ወለላ ንጉሆ ተላዒሎም ናውቲ ማሕረሶም ኣዋዲዶም ምስ ኣብዑሮም እናተዛረቡ ይሓርሱ ነበሩ ። ወይዘሮ ህይወት ግና ብሃንደበታዊ ሞት በዓል ገዝኣ ብሓዘን ተዀርምያ ብዛዕባ መፃኢ ህይወታን ህይወት ክልተ ደቃን ትሓስብ ነበረት ። ኣብዚ እዋን ግራታ ስኣን ዝሓርሰላ ባዲሙ ከይተርፍ እውን ሰግአት ። ኣብ ከምዚ ፀገም እናሃለወት ተስፋይ ትምህርቲ ከምዘቋርፅ ነገራ ። ወይዘሮ ህይወት ሓዘን እናተሰመዓ ንምንታይ ወደዋይ ኢላ ሓተተቶ ግራትና ክሓርስ  በላ ኣዲኡ መልሲ ከይሃበት ኣብ ሓሳብ ጠሓለት። ",
          "qas": [
            {
              "id": "39_Q1",
              "question": "ሓረስቶት ጣብያ  ሓዱሽ ዓለም ቁሸት ወለላ፣ ዝሓረሱሉ ወርሒ እንታይ ነበረ?",
              "answers": [
                {
                  "text": "ግንቦት",
                  "answer_start": 9,
                  "answer_end": 14
                }
              ]
            },
            {
              "id": "39_Q2",
              "question": "ሓረስቶት ናውቲ ማሕረሶም ኣዋዲዶም ምስ መን እናተዛረቡ ይሓርሱ ነበሩ?",
              "answers": [
                {
                  "text": "ምስ ኣብዑሮም",
                  "answer_start": 66,
                  "answer_end": 76
                }
              ]
            },
            {
              "id": "39_Q3",
              "question": "ወይዘሮ ህይወት ብዛዕባ እንታይን መንን ትሓስ",
              "answers": [
                {
                  "text": "ብዛዕባ መፃኢ ህይወታን ህይወት ክልተ ደቃን",
                  "answer_start": 137,
                  "answer_end": 166
                }
              ]
            },
            {
              "id": "39_Q4",
              "question": "ወይዘሮ ህይወት ኣብዚ እዋን ግራታ ስኣን እንታይ ባዲሙ ከይተርፍ ሰግአት?",
              "answers": [
                {
                  "text": "ዝሓርሰላ",
                  "answer_start": 219,
                  "answer_end": 226
                }
              ]
            }
          ]
        }
      ]
    }
  ],
  
  "data": [
    {
      "title": "Context 40: Sample Title",
      "paragraphs": [
        {
          "context": "ንኹሉ  ነገር ኣመዛዚና ደቃ ትምህርቲ ከቋርፁ ከም ዘይብሎምን ግራታ ባዕላ ክትሓርስን ወሰነት። ውሳነኣ ንደቃ ነገረቶም ንሳቶም  ድማ  ስራሕቲ  ገዛ  ባዕልቶም  ክሽፍኑ  ተስማዕምዑ ። ንፅባሒቱ ወይዘሮ ህይወት መሳርዕ ኣዋዲዳ ዕማማት ክተሳልጥ ጀመረት ። ደቃ ምግቢ ኣብ ደረት ገዲፎሙላ ናበይ ከዱ ። ወይዘሮ ህይወት እናሓረሰት ዝረኣዩዋ ኣዝማዳ ፣ ዓዲ ካብ ተፅርፍ ባዕሎም ንኽሓርሱላ ነገርዋ ። ህይወት ግና ባዕለይ ክሰርሖ ዝኽእል ሰብ ክሰርሐለይ ኣይደልን ኢላ ስርሓ ቀፀለት ።",
          "qas": [
            {
              "id": "40_Q1",
              "question": "ወይዘሮ ህይወት እንታይ ወሰነት?",
              "answers": [
                {
                  "text": "ደቃ ትምህርቲ ከቋርፁ ከም ዘይብሎምን",
                  "answer_start": 0,
                  "answer_end": 37
                }
              ]
            },
            {
              "id": "40_Q2",
              "question": "ወይዘሮ ህይወት ውሳነኣ ንመን ነገረቶም?",
              "answers": [
                {
                  "text": "ንደቃ",
                  "answer_start": 47,
                  "answer_end": 52
                }
              ]
            },
            {
              "id": "40_Q3",
              "question": "ደቃ እንታይ ክገብሩ ተሰማምዑ?",
              "answers": [
                {
                  "text": "ስራሕቲ ገዛ ባዕልቶም ክሽፍኑ",
                  "answer_start": 90,
                  "answer_end": 116
                }
              ]
            },
            {
              "id": "40_Q4",
              "question": "ደቃ ምግቢ ኣብ ደረት ገዲፎሙላ ናበይ ከዱ?",
              "answers": [
                {
                  "text": "ቤት ትምህርቲ",
                  "answer_start": 140,
                  "answer_end": 148
                }
              ]
            },
            {
              "id": "40_Q5",
              "question": "ወይዘሮ ህይወት እናሓረሰት ዝረኣዩዋ ኣዝማዳ እንታይ በሉዋ?",
              "answers": [
                {
                  "text": "ዓዲ ካብ ተፅርፍ ባዕሎም ንኽሓርሱላ ነገርዋ",
                  "answer_start": 254,
                  "answer_end": 287
                }
              ]
            }
          ]
        }
      ]
    }
  ],
  
  "data": [
    {
      "title": "Context 33: Sample Title",
      "paragraphs": [
        {
          "context": "እዚ መጠን ነቶም ገዛ ዘይብሎም ኣይሓውስን ። ሕብረተሰብ ዓለም ኮነ ሃገርና ብዛዕባ እንታይነትን መንቀሊን ጉድኣት ኣካል እኹል ግንዛበ ክረክብ ኣለዎ ። ብመሰረት እቲ ግንዛበ ቕልጡፍን ዝተዋደደን ስጉምቲ እንተዘይ ተወሲዱ እዚ ቝፅሪ ከም ዝውስኽ ይግመት ። ጉድኣት ኣካል ወገናት ጠቕሊሎም ኣብ ዓውደ ስራሕ ኮነ ትምህርቲ ተዋፊሮም ዘዕግብ ውፅኢት ካብ ምምዝጋብ ዝእግድ ኣይኮነን ። ዝሰርሑሉ ቦታን ኩነታትን እንተተመቻችዩሎም ዓርሶም ይኽእሉ ።",
          "qas": [
            {
              "id": "33_Q1",
              "question": "መጠን ጉዱኣት ኣካል ንመን ኣይሓውስን?",
              "answers": [
                {
                  "text": "ገዛ ዘይብሎም",
                  "answer_start": 21,
                  "answer_end": 35
                }
              ]
            },
            {
              "id": "33_Q2",
              "question": "ብዛዕባ እንታይነትን መንቀሊን ጉድኣት ኣካል መን እኹል ግንዛበ ክረክብ ዘለዎ መን እዩ?",
              "answers": [
                {
                  "text": "ሕብረተሰብ ዓለም ኮነ ሃገርና",
                  "answer_start": 67,
                  "answer_end": 87
                }
              ]
            },
            {
              "id": "33_Q3",
              "question": "እንታይ  ስጉምቲ እንተዘይተወሲዱ እዩ እዚ ቝፅሪ ከም ዝውስኽ ዝግመት?",
              "answers": [
                {
                  "text": "ቕልጡፍን ዝተዋደደን",
                  "answer_start": 129,
                  "answer_end": 147
                }
              ]
            },
            {
              "id": "33_Q4",
              "question": "ጉድኣት  ኣካል ወገናት ኣብ ዓውደ ስራሕ ኮነ ትምህርቲ ተዋፊሮም ፣እንታይ ካብ ምምዝጋብ ዝእግድ ኣይኮነን?",
              "answers": [
                {
                  "text": "ዘዕግብ ውፅኢት",
                  "answer_start": 195,
                  "answer_end": 209
                }
              ]
            },
            {
              "id": "33_Q5",
              "question": "እንታይ እንተተመቻችዩሎም እዮም ዓርሶም ዝኽእሉ?",
              "answers": [
                {
                  "text": "ዝሰርሑሉ ቦታን ኩነታትን",
                  "answer_start": 281,
                  "answer_end": 303
                }
              ]
            }
          ]
        }
      ]
    }
  ],
  
  "data": [
    {
      "title": "Context 10: Sample Title",
      "paragraphs": [
        {
          "context": "ከልቢ ግና  እንታይ‘ሞ ክገብር  ኣብዘይ ሞያይ ኣትየ ኢሉ መጐተ። ዒፍ ሓዚና ናብ ገዝኣ ተመሊሳ ዝረኣየቶ ኩሉ ንኣንጨዋ ነገረታ ። ኣብቲ እዋን ኣንጭዋ ፀብሒ እንትተሕብር ኢዳ ተለብለበት ። ዒፍ ድማ ማይ ሒዛ ክትምለስ መገለል ካብ እግራ መሊቑ ናብ ጉድጓድ ኣተወ ። ካሊእ መዓልቲ ሰለስቲኦም ብዛዕባ ዘጋጠሞም ፀገም ዘተዩ ። ዒፍ ይቕረታ ሓተተት ። ኣብ መወዳእታ ሕድ ሕዶም ናብ ናይ ቀደም ስረሖም ተመሊሶም ቀሲኖም ምንባር ቀፀሉ ይበሃል ።",
          "qas": [
            {
              "id": "10_Q1",
              "question": "መን እዩ ኣብ ዘይሞያይ ኣትየ ዝበለ?",
              "answers": [
                {
                  "text": "ከልቢ",
                  "answer_start": 0,
                  "answer_end": 5
                }
              ]
            },
            {
              "id": "10_Q2",
              "question": "ዒፍ ዝረኣየ ቶኩሉ ንመን ነገረታ?",
              "answers": [
                {
                  "text": "ንኣንጨዋ",
                  "answer_start": 58,
                  "answer_end": 65
                }
              ]
            },
            {
              "id": "10_Q3",
              "question": "ኣንጭዋ እንታይ ክትገብር ኢዳ ተለብለበት?",
              "answers": [
                {
                  "text": "ፀብሒ እንትተሕብር",
                  "answer_start": 82,
                  "answer_end": 94
                }
              ]
            },
            {
              "id": "10_Q4",
              "question": "መገለልካ ብእግሪ ዒፍሞሊቑናብእንታይኣተወ?",
              "answers": [
                {
                  "text": "ናብጉድጓድ",
                  "answer_start": 221,
                  "answer_end": 229
                }
              ]
            },
            {
              "id": "10_Q5",
              "question": "ሰለስቲኦም ብዛዕባ እንታይ ዘተዩ?",
              "answers": [
                {
                  "text": "ብዛዕባ ዘጋጠሞም ፀገም",
                  "answer_start": 261,
                  "answer_end": 276
                }
              ]
            }
          ]
        }
      ]
    },
    {
      "title": "Context 32: Sample Title",
      "paragraphs": [
        {
          "context": "ጉድኣት ኣካል ብሰንኪ ሓደጋ ወይ ሕማም ዘጋጥም ናይ ኣእምሮ ስምዒት ሕዋስ ወይ ካሊእ ክፍለ ኣካል መጉዳእቲ እዩ ። ከም መግለፂ ውድብ ሕቡራት መንግስቲታት ብሰንኪ ዝተፈላለዩ መጉዳእቲታት 500 ሚልዮን ዝኾኑ ጉዱኣት ኣካል ኣለዉ ። ኣብ ሃገርና ቝፅሪ ጉዱኣት ኣካል ልዑል እዩ ። ብ 1986  ኣብ ዝተኻየደ ሃገራዊ ቆፀራ ህዝቢን ኣባይቲን  988,849  ዝኾኑ ጉዱኣት ኣካል ወገናት ከም ዘለዉ ተገሊፁ ።",
          "qas": [
            {
              "id": "32_Q1",
              "question": "ጉድኣት ኣካል ብሰንኪ እንታይ ይመፅእ?",
              "answers": [
                {
                  "text": "ሓደጋ ወይ ሕማም",
                  "answer_start": 32,
                  "answer_end": 44
                }
              ]
            },
            {
              "id": "32_Q2",
              "question": "ክንደይ ዝኾኑ ጉዱኣት ኣካል ኣለዉ?",
              "answers": [
                {
                  "text": "500 ሚልዮን",
                  "answer_start": 150,
                  "answer_end": 159
                }
              ]
            },
            {
              "id": "32_Q3",
              "question": "ኣብ ሃገርና ቝፅሪ ጉዱኣት ኣካል ትሑት ዲዩ ልዑል?",
              "answers": [
                {
                  "text": "ልዑል",
                  "answer_start": 239,
                  "answer_end": 244
                }
              ]
            },
            {
              "id": "32_Q4",
              "question": "መዓስ ብዝተኻየደ ሃገራዊ ቆፀራ ህዝቢን ኣባይቲን እዩ ቁፅሪ ጉዱኣት ኣካል ተፈሊጡ?",
              "answers": [
                {
                  "text": "ብ1986",
                  "answer_start": 264,
                  "answer_end": 269
                }
              ]
            },
            {
              "id": "32_Q5",
              "question": "ኣብ ሃገርና ቝፅሪ ጉዱኣት ክንደይ ከምዘለዉ እዩ ተገሊፁ?",
              "answers": [
                {
                  "text": "988,849",
                  "answer_start": 303,
                  "answer_end": 310
                }
              ]
            }
          ]
        }
      ]
    }
  ],
  
  "data": [
    {
      "title": "Context 9: Sample Title",
      "paragraphs": [
        {
          "context": "ኣንጭዋን ከልቢን ከም ዘይቕበሉዎ ገለፁ ። ድሕሪ ነዊሕ ክትዕ ግና ዒፍ ብዝበለቶ ተሰማዕምዑ ። ብመሰረት እቲ ሓዱሽ ለውጢ ከልቢ ዱር እናኸደ ዕንፀይቲ ከምፅእ ፣ኣንጭዋ ምግቢ ክትሰርሕ  ፣ ዒፍ ድማ ማይ ክተቕርብ ወሲኖም ነናብስርሖም ተዋፈሩ ።ኣብ ቐፃሊ መዓልቲ ምግቢ ደንጐየ ። ከልቢ ዕንፀይቲ ከምፅእ እዩ እንተተብሃለ ጠፍአ ። ስለዚ ዒፍ ደሃይ ከልቢ ንምፍላጥ ክትእልሾ ከደት ። ከልቢ ዝገብሮ ጠፊኡዎ ኮፍ ኢሉ ረኸበቶ ። ዒፍ ሓሪቓ ነቲ ከልቢ ጌገኛ ምዃኑ ነገረቶ ። ኣንጭዋ ምግቢ ክትሰርሕ  ኢዳ ተለብለበት::",
          "qas": [
            {
              "id": "9_Q1",
              "question": "ከም ዘይቕበሉዎ ዝገለፁ መን እዩ ም ?",
              "answers": [
                {
                  "text": "እንጭዋን ከልብን",
                  "answer_start": 0,
                  "answer_end": 10
                }
              ]
            },
            {
              "id": "9_Q2",
              "question": "ማይ ክተቕርብ  ንመን ወሲኖም?",
              "answers": [
                {
                  "text": "ዒፍ",
                  "answer_start": 212,
                  "answer_end": 215
                }
              ]
            },
            {
              "id": "9_Q3",
              "question": "ኣንጭዋ እንታይ ክትገብር ኢዳ ተለብለበት?",
              "answers": [
                {
                  "text": "ምግቢ ክትሰርሕ",
                  "answer_start": 256,
                  "answer_end": 268
                }
              ]
            },
            {
              "id": "9_Q4",
              "question": "ዒፍ ደሃይ  መን   ንምፍላጥ ክትእልሾ ከደት?",
              "answers": [
                {
                  "text": "ከልቢ",
                  "answer_start": 313,
                  "answer_end": 318
                }
              ]
            },
            {
              "id": "9_Q5",
              "question": "ዒፍ ሓሪቓ ነቲ ከልቢ  ታይ ምዃኑ ነገረቶ?",
              "answers": [
                {
                  "text": "ጌገኛ",
                  "answer_start": 363,
                  "answer_end": 368
                }
              ]
            }
          ]
        }
      ]
    }
  ],
    "title": "Context 43",
    "paragraphs": [
      {
        "context": "ኣብ ትግራይ ካብ ዝርከቡ ህንፃ ውቑራት ኣብያተ እምነት ኣብርሃ ወኣፅብሃ ሓደ እዩ ።እዚ ካብ ከተማ ውቕሮ ብኣንፈት ምዕራብ  15  ኪሎ ሜትር ርሒቑ ይርከብ ። ኣብርሃ ወኣፅብሃ ካብ ከውሒ ተፈልፊሉ ዝተሃንፀ ኮይኑ ካብቲ ከውሒ ምሉእ ብምሉእ ተፈልዩ ዝወፀ ኣይኮነን ። ብቕድሚቱን ብኽልተ ጎኑን ካብቲ ከውሒ ዝተፈለየ ኮይኑ ብድሕሪቱ ግና ምስቲ ከውሒ ዝተተሓሓዘ እዩ ።",
        "qas": [
          {
            "id": "43_Q1",
            "question": "ኣብ ትግራይ ካብ ዝርከቡ ህንፃ ውቑራት ኣብያተ እምነት ሓደ መን እዩ?",
            "answers": [
              {
                "text": "ኣብርሃ ወኣፅብሃ",
                "answer_start": 44,
                "answer_end": 56
              }
            ]
          },
          {
            "id": "43_Q2",
            "question": "ኣብርሃ ወኣፅብሃ ካብ ከተማ ውቕሮ ክንደይ ኪሎ ሜትር ርሒቑ ይርከብ?",
            "answers": [
              {
                "text": "15 ኪ/ሜ",
                "answer_start": 116,
                "answer_end": 123
              }
            ]
          },
          {
            "id": "43_Q3",
            "question": "ኣብርሃ ወኣፅብሃ ካብ  ምንታይ ተፈልፊሉ ዝተሃንፀ እዩ?",
            "answers": [
              {
                "text": "ከውሒ",
                "answer_start": 163,
                "answer_end": 168
              }
            ]
          },
          {
            "id": "43_Q4",
            "question": "ኣብርሃ ወኣፅብሃ ካብ ከተማ ውቕሮ ብኣንፈት እንታይ ይርከብ?",
            "answers": [
              {
                "text": "ምዕራብ",
                "answer_start": 214,
                "answer_end": 221
              }
            ]
          },
          {
            "id": "43_Q5",
            "question": "ኣብርሃ ወኣፅብሃ ብኽንደይ ጎኑ ካብቲ ከውሒ ዝተፈለየ እዩ?",
            "answers": [
              {
                "text": "ብኽልተ ጎኑ",
                "answer_start": 294,
                "answer_end": 302
              }
            ]
          }
        ]
      }
    ],  "title": "Context 44",
    "paragraphs": [
      {
        "context": "ኣብርሃ ወኣፅብሃ ቅርፂ መስቀል ዘለዎ ኮይኑ ስፍሓቱ  16 ሜትር ብ13 ሜትር እዩ ። ቁመት ናሕሱ ሸውዓተ ሜትር ይበፅሕ ። ነቲ ናሕሲ ህንፃ ዝደገፉ  13  ዓበይቲ ዓምዲታት ዘለዉዎ እንትኸውን ብስእሊ ዝተመላኸዐ እዩ ። ኣብ ውሽጡ ኣዝዩ ረቂቕ ዝበሃል ጥበብ ኣቀራርፃ ዝረአየሉ እዩ ። ውሽጣዊ ገይፂታትን ጥበብ ኣተሃናንፃ ኣብርሃ ወኣፅብሃ ኣዝዩ ዘደምም እዩ ።",
        "qas": [
          {
            "id": "44_Q1",
            "question": "ቅርፂ ኣብርሃ ወኣፅብሃ እንታይ ይመስል?",
            "answers": [
              {
                "text": "መስቀል",
                "answer_start": 21,
                "answer_end": 26
              }
            ]
          },
          {
            "id": "44_Q2",
            "question": "ስፍሓቱ ኣብርሃ ወኣፅብሃ ክንደይ ብኽንደይ ሜትር እዩ?",
            "answers": [
              {
                "text": "16 ብ13ሜ",
                "answer_start": 43,
                "answer_end": 52
              }
            ]
          },
          {
            "id": "44_Q3",
            "question": "ቁመት ናሕሲ ኣብርሃ ወኣፅብሃ ክንደይ ሜትር ይበፅሕ?",
            "answers": [
              {
                "text": "7ሜ",
                "answer_start": 79,
                "answer_end": 83
              }
            ]
          },
          {
            "id": "44_Q4",
            "question": "ናሕሲ ኣብርሃ ወኣፅብሃ ብኽንደይ ዓበይቲ ዓምዲታት ተደጊፉ?",
            "answers": [
              {
                "text": "13",
                "answer_start": 122,
                "answer_end": 124
              }
            ]
          },
          {
            "id": "44_Q5",
            "question": "ኣብ ኣብርሃ ወኣፅብሃ ኣዝዩ ዘደምም እንታይ እዩ?",
            "answers": [
              {
                "text": "ውሽጣዊ ገይፂታትን ጥበብ ኣተሃናንፃን",
                "answer_start": 219,
                "answer_end": 239
              }
            ]
          }
        ]
      }
    ],
    "title": "Context 46",
    "paragraphs": [
      {
        "context": "ስመይ ሚኪ ግርማይ ይበሃል ። ሓደ መዓልቲ ዘጋጠመኒ ነገር ክነግረኩም ። ኣቦ ሓጎይ ካብ ገፀር ክጥይቐና ካብ ዝመፅእ ሓደ ወርሒ ገይሩ ነበረ ሓደ ሰንበት ከምቲ ኩሉ ግዘ ዝገብሮ ኣብ ከባቢና ካብ ዝርከብ ቤት መካረዪ ካሴታት ንምሉእ መዓልተይ ዝኸውን ኣርባዕተ ናይ ወፃእ ፊልሚታት ተኻረኹ ። ካብ ንግሆ ጀሚረ ምስ ዝኾነ ኣባል ስድራቤተይ ከይተዛረብኩ ኣብ ጥቓ እታ ቴለቭዥን ተወተፍኩ ። ኣቦሓጎይ ኩነታተይ ደስ ከም ዘይበሎ  የፍልጥ  ነበረ ።",
        "qas": [
          {
            "id": "46_Q1",
            "question": "ስም ተራኺ ታሪኽ መንይበሃል?",
            "answers": [
              {
                "text": "ሚኪ ግርማይ",
                "answer_start": 6,
                "answer_end": 15
              }
            ]
          },
          {
            "id": "46_Q2",
            "question": "ሚኪ ግርማይ እንታይ እዩ ክነግረና?",
            "answers": [
              {
                "text": "ሓደ መዓልቲ ዘጋጠሞ ነገር",
                "answer_start": 21,
                "answer_end": 38
              }
            ]
          },
          {
            "id": "46_Q3",
            "question": "ኣቦሓጎ ሚኪ ግርማይ ካበይ እዮም መፂኦም?",
            "answers": [
              {
                "text": "ገፀር",
                "answer_start": 54,
                "answer_end": 58
              }
            ]
          },
          {
            "id": "46_Q4",
            "question": "ሚኪ ክንደይ ካሴታት ፊልሚ ተኻረየ?",
            "answers": [
              {
                "text": "ኣርባዕተ",
                "answer_start": 117,
                "answer_end": 124
              }
            ]
          },
          {
            "id": "46_Q5",
            "question": "ሚኪ፣ ኩነታተይደስከምዘይበሎየፍልጥነበረ፣ ዝበሎ ንመን እዩ?",
            "answers": [
              {
                "text": "ንኣቦ ሓጎኡ",
                "answer_start": 141,
                "answer_end": 152
              }
            ]
          }
        ]
      }
    ],"title": "Context 47",
    "paragraphs": [
      {
        "context": "ክልተ ፊልሚታት ርእየ ኣብ ጎኒ ኣቦ ሓጎይ ኮፍ በልኩ ።ከዛርቦ ደልየ ፣ ጎይታይ ተፃወት በልኩዎ ። ተጐምጒሙዎ ዝነበረ ኩታ ኣውሪዱ ፣ እንታይ ክፃወተሉ በለኒ ። ብኣዘራርብኡ ደንጊፀ  ከመይ  በልኩዎ ኩሉ ነገርካ ድምፆም ብዘይስማዕ ፀዓዱ ተሰሊቡ ፤ ኣብዚ በይንኻ ተዀርሚኻ ከም ዕቡድ በሎ በሎ ካብ ትብልሲ ካልእ ፀወታ ዘይትፃወት ኢሉ መለሰለይ  ክረድኦ ኢለ ብዛዕባ ረብሓ ምርኣይ ፊልሚታት ዘርዘርኩሉ ኣቦሓጎይ ፈፂሙ ባህ ኣይበሎን ።",
        "qas": [
          {
            "id": "47_Q1",
            "question": "ሚኪ ክንደይ ፊልሚ ሪኡ እዩ ኣብ ጎኒ ኣቦ ሓጉኡ ኮፍ ዝበለ?",
            "answers": [
              {
                "text": "ክልተ",
                "answer_start": 0,
                "answer_end": 4
              }
            ]
          },
          {
            "id": "47_Q2",
            "question": "ሚኪ “ጎይታይተፃወት” ዝበሎ ንመን እዩ?",
            "answers": [
              {
                "text": "ንሓቦሓጎኡ",
                "answer_start": 24,
                "answer_end": 35
              }
            ]
          },
          {
            "id": "47_Q3",
            "question": "ኣቦ ሓጉኡ ንሚኪ ተጐምጒሞሙዎ ዝነበረ  ኩታ እንታይ ገበሩዎ?",
            "answers": [
              {
                "text": "ኣውረድዎ",
                "answer_start": 53,
                "answer_end": 59
              }
            ]
          },
          {
            "id": "47_Q4",
            "question": "ሚክ ብኣዘራርባ ኣቦ ሓጉኡ እንታይ ኮነ?",
            "answers": [
              {
                "text": "ደንጊፁ",
                "answer_start": 75,
                "answer_end": 81
              }
            ]
          },
          {
            "id": "47_Q5",
            "question": "ኣቦ ሓጎ ሚኪ እንታይ እዩ  ባህ  ዜበሎም?",
            "answers": [
              {
                "text": "ብዛዕባ ረብሓ ምርኣይ ፊልሚ",
                "answer_start": 166,
                "answer_end": 182
              }
            ]
          }
        ]
      }
    ],"title": "Context 48",
    "paragraphs": [
      {
        "context": "ወግዒ ከየቋርፅ ምእንታን ፣ ጎይታይ  ክንዳና እናሃለኹም ብምንታይ ትዛናግዑ ነይርኩም ኢለ ሓተትኩዎ ።ንውሱናት ሰከንድታት ኣብ ሓሳብ  ጥሒሉ  ድሕሪ  ምፅናሕ ፣ ኣብ ባህልና ካብ ህፃንነት ክሳብ ሽምግልና ኣብ ዘሎ   ዕድመ ጭዋዳና ዘጠንክሩ ፣ ኣተሓሳስባና ዘብልሑ ፣ ዘመራምሩ ፣ ዘስሕቁ ፣ ነፃ ስምዒት ንገልፀሎም መዘናግዒታት ኣለዉና  በለኒ  ካብቶም መዘናግዒታት ክዝርዝረለይ ጠየቕኩዎ ምንቅስቓስ ኣካል ካብ ዝፍፀሙ ፣ ቃርሳ ፣ቅልስ ፣ እዛ እምባይ መን ይወርሳ ፣ ተወሰጥ ፣ እሕምባየ እሕምባዛ ፣ ፍቲፍቲ እንትኾኑ ብምሕሳብን ብምምርማርን ዝትግበሩ ድማ ከም ገበጣ ፣ ሽታ ፣ኣቀራቃር ፣ ዲቦ ፣ ነበራ ያነበረ ፣ ሕንቅልሕንቅሊተይ ፣  እንካኣዝግነንን ካልኦት ኣብ ዝተፈላለዩ ክብረ በዓላት ዝበሃሉ መዘናግዒታት ነገረኒ ።",
        "qas": [
          {
            "id": "48_Q1",
            "question": "“ጎይታይ! ክንዳና እናሃለኹም ብምንታይ ትዛናግዑ ነይርኩም?” ኢሉ ዝሓተተ መን እዩ?",
            "answers": [
              {
                "text": "ሚኪ ግርማይ",
                "answer_start": 171,
                "answer_end": 181
              }
            ]
          },
          {
            "id": "48_Q2",
            "question": "ንውሱናት ሰከንድታት ኣብ ሓሳብ ጥሒሉ ድሕሪ ምፅናሕ ፣ ኣብ ባህልና ካብ ህፃንነት ክሳብ ሽምግልና ኣብ ዘሎ ዕድመ ጭዋዳና ዘጠንክሩ ፣ ኣተሓሳስባና ዘብልሑ ፣ ዘመራምሩ ፣ ዘስሕቁ ፣ ነፃ ስምዒት ንገልፀሎም መዘናግዒታት ኣለዉና  በለኒ  ካብቶም መዘናግዒታት ክዝርዝረለይ ጠየቕኩዎ ምንቅስቓስ ኣካል ካብ ዝፍፀሙ ፣ ቃርሳ ፣ቅልስ ፣ እዛ እምባይ መን ይወርሳ ፣ ተወሰጥ ፣ እሕምባየ እሕምባዛ ፣ ፍቲፍቲ እንትኾኑ ብምሕሳብን ብምምርማርን ዝትግበሩ ድማ ከም ገበጣ ፣ ሽታ ፣ኣቀራቃር ፣ ዲቦ ፣ ነበራ ያነበረ ፣ ሕንቅልሕንቅሊተይ ፣  እንካኣዝግነንን ካልኦት ኣብ ዝተፈላለዩ ክብረ በዓላት ዝበሃሉ መዘናግዒታት ነገረኒ ።",
            "answers": [
              {
                "text": "አባሓጎ ሚኪ",
                "answer_start": 181,
                "answer_end": 193
              }
            ]
          },
          {
            "id": "48_Q3",
            "question": "ጭዋዳና ዘጠንክሩ፣ኣተሓሳስባናዘብልሑ፣ እተባህሉ እንታይ እዮም?",
            "answers": [
              {
                "text": "መዘናግዕታት",
                "answer_start": 545,
                "answer_end": 552
              }
            ]
          },
          {
            "id": "48_Q4",
            "question": "ቅልስ ንእዛ እምባይ መን ይወርሳ ንብመንታይ ዝፍፀሙ መዘናጊዕታት እዮም?",
            "answers": [
              {
                "text": "ብምንቅስቓስ",
                "answer_start": 617,
                "answer_end": 627
              }
            ]
          },
          {
            "id": "48_Q5",
            "question": "ብምሕሳብን ብምምርማርን ዝትግበሩ መዘናጊዒታት ኣየኖት እዮም?",
            "answers": [
              {
                "text": "ገበጣ 'ሽታ ኣቀራቃር' ዲቦ' ነበረያነበረ፣ሕንቅሕንቅሊተይን እንካኣዝግንን",
                "answer_start": 701,
                "answer_end": 749
              }
            ]
          }
        ]
      }
    ],
    "title": "Context 49",
    "paragraphs": [
      {
        "context": "ካብ እዞም ኣቦሓጎይ ዝዘርዘሮም መዘናግዒታት ሓደ ብዘይምፍላጠይ ሓፈርኩ ። ኣብ መንጎና ዘሎ ኣፈላላይ ኣተሓሳሰበኒ ። ኣብ መወዳእታ ብውሽጠይ እዚ ነገር ኣብ በይነይ ድዩ ኣብ ካልኦት መናእሰይ እዚ ዘበን እውን  በልኩ ።",
        "qas": [
          {
            "id": "49_Q1",
            "question": "ሚኪ ብምንታይ ሓፈረ?",
            "answers": [
              {
                "text": "ብዘይምፍላጡ",
                "answer_start": 0,
                "answer_end": 40
              }
            ]
          },
          {
            "id": "49_Q2",
            "question": "ሚኪ እንታይ ኣይፈልጥን?",
            "answers": [
              {
                "text": "ባህላዊ መዘናግዕታት",
                "answer_start": 116,
                "answer_end": 131
              }
            ]
          },
          {
            "id": "49_Q3",
            "question": "ሚኪ “ኣብ መንጎና ዘሎ ኣፈላላይ” ክብል ከሎ፣ ኣብ መንጎ መንን መንን እዩ?",
            "answers": [
              {
                "text": "ኣብ መንጉኡን ኣብ ሞንጎ ኣቦሓጎኡን",
                "answer_start": 154,
                "answer_end": 192
              }
            ]
          },
          {
            "id": "49_Q4",
            "question": "“እዚ ነገር ኣብ በይነይ ድዩ ኣብ ካልኦት መናእሰይ ዝበለ መን እዩ?",
            "answers": [
              {
                "text": "ሚኪ",
                "answer_start": 258,
                "answer_end": 262
              }
            ]
          },
          {
            "id": "49_Q5",
            "question": "ኣብ መንጎኦም ዘሎ ኣፈላላይ እንታይ ገይርዎ?",
            "answers": [
              {
                "text": "ኣተሓሳሲብዎ",
                "answer_start": 298,
                "answer_end": 307
              }
            ]
          }
        ]
      }
    ],
    "title": "Context 50",
    "paragraphs": [
      {
        "context": "ኣብ ሃገርና ዝርከቡ እንስሳ ዘገዳም ካብ ዘይሕጋዊ ሃደንቲ ንምክልኻልን ምቹው ከባቢ ንምፍጣርን ሰፋሕቲ ቦታታት ተሓዚኦም እዮም ። እዞም ሕዛእቲታት ሃገራዊ ፓርክታት ይበሃሉ ። ኣብ ኢትዮጵያ ዓሰርተ ሃገራዊ ፓርክታት ኣለዉ ። ኣብዞም ፓርክታት ዝተፈላለዩ ሳዕሪን ቆፅሊን ከምኡ እውን ስጋ ተመገብቲ እንስሳት ዘገዳም ይርከቡ ። ካብዞም ነባራት ዓሰርተ ሃገራዊ ፓርክታት ብተወሳኺ ትግራይ ዝርከብ ቃፍታ-ሸራሮ ዝብሃል ሓዱሽ ፓርክ ኣሎ ።",
        "qas": [
          {
            "id": "50_Q1",
            "question": "ሰፋሕቲ ቦታታት ንምንታይ ተሓዚኦም?",
            "answers": [
              {
                "text": "ካብ ዘይሕጋዊ ሃደንቲ ንምክልኻልን ምቹው ከባቢ ንምፍጣርን",
                "answer_start": 31,
                "answer_end": 78
              }
            ]
          },
          {
            "id": "50_Q2",
            "question": "ሕዛእቲታት እንስሳ ዘገዳም እንታይ ይበሃሉ?",
            "answers": [
              {
                "text": "ሃገራዊ ፓርክታት",
                "answer_start": 108,
                "answer_end": 122
              }
            ]
          },
          {
            "id": "50_Q3",
            "question": "ኣብ ኢትዮጵያ ክንደይ ሃገራ ዊፓርክታት ኣለዉ?",
            "answers": [
              {
                "text": "ዓሰርተ",
                "answer_start": 147,
                "answer_end": 151
              }
            ]
          },
          {
            "id": "50_Q4",
            "question": "ኣብ ፓርክታት ዝርከቡ እንስሳ ዘገዳም ተመገብቲ እንታይን እንታይን እዮም?",
            "answers": [
              {
                "text": "ሳዕሪን ቆፅሊን ከምኡ እውን ስጋ ተመገብቲ",
                "answer_start": 175,
                "answer_end": 214
              }
            ]
          },
          {
            "id": "50_Q5",
            "question": "ትግራይ ዝርከብ ሓዱሽ ፓርክ እንታይ ይበሃል?",
            "answers": [
              {
                "text": "ቃፍታ ሽራሮ",
                "answer_start": 244,
                "answer_end": 254
              }
            ]
          }
        ]
      }
    ],
    
    "title": "Context 51",
    "paragraphs": [
      {
        "context": "ሃገራዊ ፓርክ ቃፍታ-ሸራሮ ኣብ ዞባ ምዕራብ ይርከብ ። እዚ ፓርክ  5,000  ትርብዒት ኪሎ ሜትር ስፍሓት ይሽፍን ። ኣብዚ ፓርክ ብዙሓት ዓሌት እንስሳ ዘገዳምን እፅዋትን ኣለዉ ። ኣብ ፓርክ ቃፍታ-ሸራሮ 42 ዓሌታት መጥበውቲ ፣ 163 ዓሌታትኣዕዋፍ፣ 9 ዓሌታት ተስሓብቲን ከምኡ እውን ዓሳታትን ይርከቡ ።ብበዝሒ ካብ ዘለዉ እንስሳት ሓርማዝ ፣ ዓጋዘን ቆላ ፣ ሰስሓ ፣ፀላም ህበይ ፣ነብሪ ፣ ዝብኢ ፣ ማንቲለ ፣ቡዃርያ ወዘተ. ምጥቃስ ይከኣል ።",
        "qas": [
          {
            "id": "51_Q1",
            "question": "ሃገራዊ ፓርክ ቃፍታ-ሸራሮ ኣበይ ይርከብ?",
            "answers": [
              {
                "text": "ኣብ ዞባ ምዕራብ",
                "answer_start": 0,
                "answer_end": 12
              }
            ]
          },
          {
            "id": "51_Q2",
            "question": "ስፍሓት ፓርክ ቃፍታ-ሸራሮ ክንደይ እዩ?",
            "answers": [
              {
                "text": "5,000 ትርብዒት ኪሎ ሜትር",
                "answer_start": 32,
                "answer_end": 56
              }
            ]
          },
          {
            "id": "51_Q3",
            "question": "ኣብ ፓርክታት ዝርከቡ እንስሳ ዘገዳምን እፅዋትን ኣለዉ?",
            "answers": [
              {
                "text": "ዓሌትእንስሳ ዘገዳምን እፅዋትን",
                "answer_start": 92,
                "answer_end": 115
              }
            ]
          },
          {
            "id": "51_Q4",
            "question": "ኣብ ፓርክ ቃፍታ-ሸራሮ ክንደይ ዓሌታትመጥበውቲ ኣለዉ?",
            "answers": [
              {
                "text": "42 ዓሌታት መጥበውቲ",
                "answer_start": 141,
                "answer_end": 166
              }
            ]
          },
          {
            "id": "51_Q5",
            "question": "ኣብ ፓርክ ቃፍታ-ሸራሮ ብብዝሒካብ ዘለዉ እንስሳት እንታይ ይጥቀሳ?",
            "answers": [
              {
                "text": "ሓርማዝ ፣ ዓጋዘንቆላ ፣ሰስሓ ፣ፀላምህበይ፣ነብሪ፣ዝብኢ፣ማንቲለ፣ቡዃርያ",
                "answer_start": 209,
                "answer_end": 256
              }
            ]
          }
        ]
      }
    ], 
    
    "title": "Context 52",
    "paragraphs": [
      {
        "context": "ሓርማዝ ነዚ ፓርክ ፍሉይ ድምቀት ይህቦ ፤ ጐሊሁ እውንክረአ ይገብሮ ። ኣብቲ ፓርክ ዝርከብ ዘርኢ ኣፍሪካ ብምዃኑ ኣፍሪካዊ ሓርማዝ ተባሂሉ ይፍለጥ ። ሓርማዝ ስነ ምሕደራዊ ሚዛን ሓደ ከባቢ ኣብ ምሕላው ዓብዪ ግደ ኣለዎ ። እዞም ኣብ ሃገራዊ ፓርክ ቃፍታ-ሸራሮ ዝርከቡ ሓራምዝ ኩሉ ግዘ ካብ ሰነ ክሳብ ጥቅምቲ ልዕሊ 200  ኮይኖም ናብ ደቡባዊ ክፋል እቲ ፓርክ ይውሕዙ እዚ ከባቢ ዝምረፅ ምስ ዝናብ ብዝተተሓሓዘ ምኽንያት ምንቅስቓስ ሰባት ትሑት ስለ ዝኸውን እዩ ። ",
        "qas": [
          {
            "id": "52_Q1",
            "question": "ኣየናይ እንስሳ እዩ ነቲ ፓርክ ፍሉይ ድምቀት ዝህቦ?",
            "answers": [
              {
                "text": "ሓርማዝ",
                "answer_start": 0,
                "answer_end": 5
              }
            ]
          },
          {
            "id": "52_Q2",
            "question": "ኣብቲ ፓርክ ዝርከብ ዘርኢ ሓርማዝ እንታይ ይበሃል?",
            "answers": [
              {
                "text": "ኣፍሪካዊ ሓርማዝ",
                "answer_start": 48,
                "answer_end": 61
              }
            ]
          },
          {
            "id": "52_Q3",
            "question": "ኣየናይ እንስሳ እዩ ስነምሕደራዊ ሚዛን ሓደ ከባቢ ኣብም ሕላው ዓብዪ ግደ ዘለዎ?",
            "answers": [
              {
                "text": "ሓርማዝ",
                "answer_start": 137,
                "answer_end": 142
              }
            ]
          },
          {
            "id": "52_Q4",
            "question": "ኣብቲ ፓርክ ክንደይ ዝኾኑ ሓራምዝ ኣለዉ?",
            "answers": [
              {
                "text": "ልዕሊ 200",
                "answer_start": 256,
                "answer_end": 266
              }
            ]
          },
          {
            "id": "52_Q5",
            "question": "እዚ ከባቢ ዝምረፅ ምስ ዝናብ ብዝተተሓሓዘ  ምኽንያት እንታይ ስለዝኾነ እዩ?",
            "answers": [
              {
                "text": "መንበሪ ሓራምዝን",
                "answer_start": 299,
                "answer_end": 309
              }
            ]
          }
        ]
      }
    ],

    
    "title": "Context 53",
    "paragraphs": [
      {
        "context": "ብመዳይ እፅዋት እንትንርእይ ድማ ኣብዚ ፓርክ 37 ዓሌታት እፅዋት ተመዝጊቦም ይርከቡ ። ካብ ጠቕላላ እቲ ዱር 50 ሚኢታዊ ዝኸውን ብኣካቻ ዝተሸፈነ እዩ ። እዞም እፅዋት መንበሪ ሓራምዝ ካልኦት እንስሳ ዘገዳምን ስለ ዝኾኑ ኩሉ ዜጋ ብፍላይ ድማ ነበርቲ እቲ ከባቢ ኣብ ምዕቃብ እቲ ዱር ርኡይ ግደ ክፃወቱ ይግባእ ።",
        "qas": [
          {
            "id": "53_Q1",
            "question": "ኣብዚ ፓርክ ክንደይ ዓሌት እፅዋት ተመዝጊበን ኣለዋ?",
            "answers": [
              {
                "text": "37",
                "answer_start": 15,
                "answer_end": 17
              }
            ]
          },
          {
            "id": "53_Q2",
            "question": "ክንደይ ሚእታዊ እቲ ፓርክ እዩ ብኣካቻ እተሸፈነ?",
            "answers": [
              {
                "text": "50",
                "answer_start": 41,
                "answer_end": 43
              }
            ]
          },
          {
            "id": "53_Q3",
            "question": "50 ሚእታዊ እቲ ፓርክ ብምንታይ እተሸፈነ እዩ?",
            "answers": [
              {
                "text": "ብኣካቻ",
                "answer_start": 57,
                "answer_end": 62
              }
            ]
          },
          {
            "id": "53_Q4",
            "question": "ኣብ ምዕቃብ እቲ ዱር ርኡይ ግደ ክፃወቱ ዝግባኦ መን እዩ?",
            "answers": [
              {
                "text": "ነበርቲ እቲ ከባቢ",
                "answer_start": 89,
                "answer_end": 100
              }
            ],
            "id": "53_Q5",
            "question": "መንበሪ ሓራምዝን ካልኦት እስሳ ዘገዳምን እንታይ እዩ?",
            "answers": [
              {
                "text": "እፅዋት",
                "answer_start": 0,
                "answer_end": 5
              }
            ]
          }
        ]
      }
    ],
    
    "title": "Context 54",
    "paragraphs": [
      {
        "context": "ኣብ ሃገርና ዝተፈላለዩ ባህላዊ ፀወታታት ኣለዉ እዞም ፀወታታት ዝትግበሩሉ ኩነታትን ወቕቲታትን ይፈላለ እዩ ። ገሊኦም ኣብ ሃይማኖታዊን ባህላዊን ክብረ በዓላት ከምኡ እውን ኣብ ከም መርዓን ሓዘንን ዝበሉ ማሕበረሰባዊ ጉዳያት ይዝውተሩ ። ኣብዚ ሕዚ እዋን እዞም ፀወታታት ባህላዊ ስፖርት ተባሂሎም ብብርኪ ክልልን ሃገርን ግጥማት ይካየዱ እዮም ፡፡",
        "qas": [
          {
            "id": "54_Q1",
            "question": "ኣብ ሃገርና ዝተፈላለዩ ባህላዊ እንታይ ኣለዉ?",
            "answers": [
              {
                "text": "ፀወታታት",
                "answer_start": 26,
                "answer_end": 33
              }
            ]
          },
          {
            "id": "54_Q2",
            "question": "ባህላዊ ፀወታታት ዝትግበሩሉ ኩነታትን እንታይን ይፈላለ?",
            "answers": [
              {
                "text": "ወቕትታትን",
                "answer_start": 49,
                "answer_end": 58
              }
            ]
          },
          {
            "id": "54_Q3",
            "question": "ባህላዊ ፀወታታት ኣብ እንታይ ይዝውተሩ?",
            "answers": [
              {
                "text": "ኣብ ሃይማኖታዊን ባህላዊን ክብረ በዓላት",
                "answer_start": 85,
                "answer_end": 112
              }
            ]
          },
          {
            "id": "54_Q4",
            "question": "ባህላዊ ፀወታታት ኣብ ከመይ ዝበሉማሕበረሰባዊ ጉዳያት ይዝውተሩ?",
            "answers": [
              {
                "text": "ኣብ ከምመርዓን ሓዘንን",
                "answer_start": 145,
                "answer_end": 166
              }
            ]
          },
          {
            "id": "54_Q5",
            "question": "ብብርኪ ክልልን ሃገርን ግጥማት ዝካየድ  ፀወታታት ባህላዊ እንታይ እዩ?",
            "answers": [
              {
                "text": "ባህላዊ ስፖርት",
                "answer_start": 205,
                "answer_end": 217
              }
            ]
          }
        ]
      }
    ],
    "title": "Context 55",
    "paragraphs": [
      {
        "context": "ኣብ ትግራይ እውን ብርክ ት ዝበሉ ባህላዊ ፀወታታት ኣለዉ ።እዞም ፀወታታት ኣካል ብምንቅስቓስ ዝፍፀሙ እንትኸውን ተፃወቲ ስሩዕ መሸከል ፣ ጥንኩር ጭዋዳን ድልዱል ኣካልን ኽህሉዎም ይሕግዙ ። ከም ገበጣ ዝበሉ ባህላዊ ፀወታታት ድማ ኣእምሮ ንምስሓልን ንምምርማርን ይጠቕሙ ። ባህላዊ ፀወታታት ኣብ ዝተፈላለዩ ኣጋጣሚታትን በዓላትን ይዝውተሩ ። ንኣብነት ቅልስ ኣብ መብዛሕትኡ ከባቢታት ትግራይ መናእሰይ ካብ መስከረም ክሳብ ጥቅምቲ ኣብ ዘሎ ግዘ የዘውትሩ ።",
        "qas": [
          {
            "id": "55_Q1",
            "question": "ብርክት ዝበሉ ባህላዊ ፀወታታት ኣበይ ኣለዉ?",
            "answers": [
              {
                "text": "ኣብ ትግራይ",
                "answer_start": 0,
                "answer_end": 11
              }
            ]
          },
          {
            "id": "55_Q2",
            "question": "ባህላዊ ፀወታታት እንታይ ብምንቅስቓስ ይፍፀሙ?",
            "answers": [
              {
                "text": "ኣካል ብምንቅስቓስ",
                "answer_start": 61,
                "answer_end": 77
              }
            ]
          },
          {
            "id": "55_Q3",
            "question": "ኣካል ብምንቅስቓስ ዝፍፀሙ ባህላዊ ፀወታታት እንታይ ንኽህሉ ይሕግዙ?",
            "answers": [
              {
                "text": "ስሩዕ መሸከል፣ጥንኩር ጭዋዳን ድልዱል ኣካልን",
                "answer_start": 93,
                "answer_end": 112
              }
            ]
          },
          {
            "id": "55_Q4",
            "question": "ከም ገበጣ ዝበሉ ባህላዊ ፀወታታት ንምንታይ ይጠቕሙ?",
            "answers": [
              {
                "text": "ኣእምሮ ንምስሓልን ንምምርማርን",
                "answer_start": 142,
                "answer_end": 165
              }
            ]
          },
          {
            "id": "55_Q5",
            "question": "ቅልስ ኣብ መብዛሕትኡ ከባቢታት ትግራይ መናእሰይ ካብ መዓስ ክሳብ መዓስ የዘውትሩ?",
            "answers":
            [
              {
                "text": "ካብ መስከረም ክሳብ ጥቅምቲ",
                "answer_start": 184,
                "answer_end": 202
              }
            ],
          }
     }   
'''
