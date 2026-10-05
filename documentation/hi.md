<!-- ELUCENIA technical documentation · tfg-de-schwartz · hi · no clinical/professional/rights approval -->

# बच्चों की ग्लोमेरुलर फिल्ट्रेशन दर (बेडसाइड Schwartz)

[शर्तें, स्रोत और अनुमतियाँ](https://elucenia.org/hi/tools/tfg-de-schwartz)

## उपयोग कैसे करें

पोर्टल पर उपकरण का उपयोग करें या स्थानीय HTTP सर्वर के माध्यम से index.html खोलें। भाषा चुनें, फ़ील्ड भरें और गणना करें।

## इनपुट और इकाइयाँ

### लंबाई

`altura`

cm · सीमा: 40–200

### सीरम क्रिएटिनिन (एंज़ाइमैटिक विधि)

`cr`

mg/dL · सीमा: 0.1–15

## विधि का संस्करण

CKiD bedside Schwartz 2009:0.413×लंबाई/Cr IDMS; mL/min/1.73m²; CKiD U25 नहीं

## दस्तावेज़ित सूत्र

eGFR (mL/min/1.73 m²) = 0.413 × लंबाई (cm) ÷ क्रिएटिनिन (mg/dL)

Schwartz 2009 बेडसाइड सूत्र (bedside) CKiD से,एंज़ाइम अंशांकित IDMS-ट्रेसेबल क्रिएटिनिन।

## सीमाएँ और जनसमूह

यह 2009 का bedside Schwartz समीकरण है, जिसे CKiD अध्ययन में दीर्घकालिक गुर्दा रोग वाले 349 प्रतिभागियों से विकसित किया गया था; भर्ती के लिए आयु की पात्रता 1–16 वर्ष थी। क्रिएटिनिन का मापन एंज़ाइम विधि से और IDMS के अनुरेखण के साथ होना चाहिए। मूल अध्ययन ने सभी बच्चों की स्क्रीनिंग में इस समीकरण का उपयोग करने से पहले, अधिक गुर्दा कार्य वाले बच्चों में अतिरिक्त सत्यापन की आवश्यकता बताई थी। परिणाम 1.73 m² के लिए मानकीकृत अनुमान है, मापा हुआ GFR, अपने आप में निदान या दवा की खुराक नहीं; यह CKiD U25 नहीं है।

## संदर्भ

- [Schwartz GJ et al. New equations to estimate GFR in children with CKD. J Am Soc Nephrol, 2009.](https://doi.org/10.1681/ASN.2008030287)

- [Kidney Disease: Improving Global Outcomes (KDIGO) CKD Work Group. KDIGO 2024 Clinical Practice Guideline for the Evaluation and Management of Chronic Kidney Disease. Kidney Int, 2024.](https://doi.org/10.1016/j.kint.2023.10.018)

- [Original Schwartz2009;JASN20:629–637;DOI10.1681/ASN.2008030287](https://www.infectedbloodinquiry.org.uk/sites/default/files/Batch%204/Batch%204/WITN7142008%20-%20New%20equations%20to%20estimate%20GFR%20in%20children%20with%20CKD%20-%2001%20Jan%202009.pdf)

## तकनीकी परीक्षण दोहराएँ

दर्ज कृत्रिम मामलों को दोहराने के लिए इस रिपॉज़िटरी की मूल निर्देशिका में node test.cjs चलाएँ। मूल इनपुट, अपेक्षित परिणाम और सहनशीलता सीमाएँ सुरक्षित रखी गई हैं। तकनीकी परीक्षण नैदानिक सत्यापन नहीं हैं।

```sh
node test.cjs
```

tool.json में स्रोत, संस्करण और समीक्षा का दायरा दिया गया है। examples.json में कृत्रिम इनपुट और अपेक्षित परिणाम सुरक्षित हैं; results.json में प्राप्त परिणाम दर्ज हैं।

[रिकॉर्ड और संदर्भ](../tool.json) · [JavaScript कोड](../calculator.js) · [संदर्भ मामले](../examples.json) · [results.json](../results.json)

## समीक्षा और उपयोग की शर्तें

स्वतंत्र नैदानिक समीक्षा नहीं की गई है।

यह इंटरफ़ेस लेखकों द्वारा किया गया अनुवाद है, कोई आधिकारिक या प्रमाणित संस्करण नहीं। स्वतंत्र नैदानिक समीक्षा, पेशेवर भाषाई समीक्षा और उपकरणों के अधिकारों की अनुमति की प्रक्रिया पूरी नहीं हुई है।

सूत्र या वर्गीकरण का परिणाम। व्याख्या, कार्यवाही और उपयुक्तता पेशेवर मूल्यांकन और चुने गए स्रोत पर निर्भर है।

## लाइसेंस और श्रेय

Apache-2.0 केवल ELUCENIA के कोड पर लागू होता है। उपकरणों, प्रकाशनों, अनुवादों और डेटा के अधिकार उनके संबंधित अधिकारधारकों के पास रहते हैं। LICENSE और NOTICE सुरक्षित रखें।

ELUCENIA · Felipe Guedes · Copyright © 2026
