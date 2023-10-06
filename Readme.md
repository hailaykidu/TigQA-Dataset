TigQA: Question Answering in Low Resource Scenarios: Expert Annotated Dataset for Tigrinya Language

Abstract
The lack of openly available annotated datasets tailored specifically for the educational domain poses a significant challenge in low-resource African languages for NLP tasks.The objective here is to tackle the issue of scarce annotated datasets for low resource African language Tigrinya. We start by exploring Machine Translation (MT) to create a Tigrinya dataset in SQuAD format. We employ various evaluation methods, including auto translation and human comparisons and conducting error analysis. Unfortunately, the quality of auto-translation between English and Tigrinya is unsatisfactory in both directions. This quality discrepancy also affects the performance of a state-of-the-art BERT-based Question Answering (QA) model when comparing human translations to auto translations. As a result, we have crafted a new, expertly annotated Tigrinya dataset (TigQA) for reading comprehension, sourced from elementary and high school textbooks. TigQA consists of 2685 question-answer pairs across 455 pages and 537 context paragraphs, covering 122 diverse topics. To evaluate the prediction of the answer span, we used XML-R baseline model, achieving an F1 score of 66.76 and an EM of 47.07. This study makes a significant contribution to the development of resources for low-resource African languages, particularly in creating an expert-annotated dataset. It underscores the difficulties in utilizing machine translation (MT) to construct datasets for languages with scant resources, stressing the necessity for more research and progress in Tigrinya NLP and tailored QA systems for low-resource languages. The dataset and code will be accessible to the public.

Dataset

'''json

    {
      "paragraphs": [
        {
          "qas": [
            {
              "question": "ዘፍር ተፈጥሮ ሳይነስ ዝኾነ ብዛዕባ ህይወታውያን ዘፅንዕ ታይ ይብሃል?\n",
              "id": 1170548,
              "answers": [
                {
                  "answer_id": 1074894,
                  "document_id": 1726204,
                  "question_id": 1170548,
                  "text": "ስነህይወት",
                  "answer_start": 1,
                  "answer_end": 7,
                  "answer_category": null
                }
              ],
              "is_impossible": false
            },
            {
              "question": "ምህዞታት ቴክኖሎጂ ዝኾኑ ማተርያላት ዘርዝር?\n",
              "id": 1170550,
              "answers": [
                {
                  "answer_id": 1074941,
                  "document_id": 1726204,
                  "question_id": 1170550,
                  "text": "ማሽን፣ ሃርድዌር",
                  "answer_start": 91,
                  "answer_end": 101,
                  "answer_category": null
                }
              ],
              "is_impossible": false
            },
            {
              "question": "ቴክኖሎጂ ንሕብረተሰብ ዝበለፀ ግልጋሎት  ንኽህብ ታይ ክገብር ይግባእ?\n\n",
              "id": 1170549,
              "answers": [
                {
                  "answer_id": 1074972,
                  "document_id": 1726204,
                  "question_id": 1170549,
                  "text": "ጥበባዊ ምምሕያሽን ምዕባለን",
                  "answer_start": 379,
                  "answer_end": 396,
                  "answer_category": null
                }
              ],
              "is_impossible": false
            },
            {
              "question": "ብሕክምና ንኸገልግሉ ዝተፈብረኩ መሳርሕታት እንታይ እዮም?\n",
              "id": 1170551,
              "answers": [
                {
                  "answer_id": 1074977,
                  "document_id": 1726204,
                  "question_id": 1170551,
                  "text": "ምህዞታት ቴክኖሎጂ",
                  "answer_start": 253,
                  "answer_end": 264,
                  "answer_category": null
                }
              ],
              "is_impossible": false
            },
            {
              "question": "ሂውት ዘለዎምን ዘይብሎምን እንሣሳት አበይ ይርከቡ?",
              "id": 1170552,
              "answers": [],
              "is_impossible": true
            }
          ],
          "context": "﻿ስነህይወት ሓደ ዘፈር ተፈጥሮ ሳይንስ ኮይኑ ብዛዕባ ህይወታውያን ዘፅንዕ እዩ። ቴክኖሎጂ ድማ ሳይንስ ወይ ጥበብ ኮይኑ ወድሰብ ዝጥቀመሎም ከም ማሽን፣ ሃርድዌር፣ ወዘተ ዝበሉ መሳርሕታት ዘማዕብል እዩ። ስነህይወት ንደቂ ሰባት ብብዙሕ መዳይ ይሕግዝ እዩ። ኣብነት ብመዳይ ሕክምና፣ ሕርሻ፣ ከባብን ቁፅፅር ማሕበረውልቀሄት ወይ ስነህዝብን ዓብዪ ረብሓ ኣለዎ። ስነህይወት ንሕብረተሰብ ብብቕዓት ንኸገልግል ምህዞታት ቴክኖሎጂ ዝኾኑ ማተርያላትን መሳርሕታትን ይጠልብ። ስነህይወት ፍልጠት ምህዞታት ቴክኖሎጂ ከምዝጠልብ ቴክኖሎጂ'ውን ፍልጠት ስነህይወት ይጠልብ። ቴክኖሎጂ ዝበለፀ ግልጋሎት ንሕብረተሰብ ንኽህብ ጥበባዊ ምምሕያሽን ምዕባለን ክገብር ይግባእ። \n",
          "document_id": 1726204
        }
      ]
    }
  ]
}        
                
}'''
