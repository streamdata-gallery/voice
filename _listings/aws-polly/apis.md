---
name: AWS Polly
description: Amazon Polly is a service that turns text into lifelike speech. Polly
  lets you create applications that talk, enabling you to build entirely new categories
  of speech-enabled products. Polly is an Amazon AI service that uses advanced deep
  learning technologies to synthesize speech that sounds like a human voice. Polly
  includes 47 lifelike voices spread across 24 languages, so you can select the ideal
  voice and build speech-enabled applications that work in many different countries.nAmazon
  Polly delivers the consistently fast response times required to support real-time,
  interactive dialog. You can cache and save Pollyrsquo;s speech audio to replay offline
  or redistribute. And Polly is easy to use. You simply send the text you want converted
  into speech to the Polly API, and Polly immediately returns the audio stream to
  your application so your application can play it directly or store it in a standard
  audio file format, such as MP3.nWith Polly, you only pay for the number of characters
  you convert to speech, and you can save and replay Pollyrsquo;s generated speech.
  Pollyrsquo;s low cost per character converted, and lack of restrictions on storage
  and reuse of voice output, make it a cost-effective way to enable Text-to-Speech
  everywhere.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-polly.jpg
x-kinRank: "10"
x-alexaRank: ""
tags:
- Voice
- Text
- Stack Network
- Speech
- Amazon Web Services
created: "2018-02-26"
modified: "2018-02-26"
url: https://raw.githubusercontent.com/streamdata-gallery/voice/master/_listings/aws-polly/apis.yaml
specificationVersion: "0.14"
apis:
- name: AWS Polly API
  description: Amazon Polly is a service that turns text into lifelike speech
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-polly.jpg
  humanURL: ""
  baseURL: :///
  tags: Voice
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery/voice/master/_listings/aws-polly/action-synthesizespeech-get.md
x-common:
- type: x-authentication
  url: http://docs.aws.amazon.com/polly/latest/dg/authentication-and-access-control.html
- type: x-customers
  url: https://aws.amazon.com/polly/customers/
- type: x-documentation
  url: http://docs.aws.amazon.com/polly/latest/dg/API_Reference.html
- type: x-faq
  url: https://aws.amazon.com/polly/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/polly/getting-started/
- type: x-logging
  url: http://docs.aws.amazon.com/polly/latest/dg/logging-using-cloudtrail.html
- type: x-monitoring
  url: http://docs.aws.amazon.com/polly/latest/dg/cloud-watch.html
- type: x-pricing
  url: https://aws.amazon.com/polly/pricing/
- type: x-website
  url: https://aws.amazon.com/polly/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---