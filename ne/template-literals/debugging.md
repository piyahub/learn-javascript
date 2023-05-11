# डिबगिंग

प्रोग्रामिंगमा, कोड लेख्दा त्रुटिहरू हुन सक्छ। यो वाक्यात्मक वा तार्किक त्रुटिहरूको कारण हुन सक्छ। त्रुटिहरू फेला पार्ने प्रक्रिया समय-खपत र पेचिलो हुन सक्छ र यसलाई कोड डिबगिंग भनिन्छ।

सौभाग्यवश, अधिकांश आधुनिक ब्राउजरहरू बिल्ट-इन डिबगरहरूसँग आउँछन्। यी डिबगरहरू स्विच अन र अफ गर्न सकिन्छ, जसले त्रुटिहरू रिपोर्ट गर्न बाध्य पार्छ। कार्यान्वयन रोक्न र चरहरूको जाँच गर्न कोडको कार्यान्वयनको क्रममा ब्रेकपोइन्टहरू सेट अप गर्न पनि सम्भव छ। यसको लागि डिबगिङ विन्डो खोल्नुपर्छ र जाभास्क्रिप्ट कोडमा 'डिबगर' कीवर्ड राख्नुपर्छ। कोड कार्यान्वयन प्रत्येक ब्रेकपोइन्टमा रोकिन्छ, विकासकर्ताहरूलाई जाभास्क्रिप्ट मानहरू जाँच गर्न र कोडको कार्यान्वयन पुन: सुरु गर्न अनुमति दिन्छ।

डिबगर सञ्झ्यालमा जाभास्क्रिप्ट मान मुद्रण गर्न `console.log()` विधि पनि प्रयोग गर्न सकिन्छ ।

```javascript
const a = 5, b = 6;
const c = a + b;
console.log(c);
// Result : c = 11;
```