# AI-Guide
An end-to-end AI guide that can help you get your right benefit from government schemes 

Meet Ram Lal, a farmer in Maharashtra, whose mother fell sick last year. For her treatment , he did many rounds of hospital, and was told total cost of treatment would be 10 lakhs. Unable to afford that much, he tragically lost his mother. Later he came to know from a friend about PM Jan Arogya Yojana which would’ve helped him get the benefits and save his mother. there are countless stories people who miss opportunities due to lack of money and resources. A lot of people can be helped by schemes which are specifically meant for them. but they are unable to avail it and that is what we’re working to change. 

Less than 10% of people know about all government schemes they are eligible for and only about 2% can avail them seamlessly. This leads to loss on both sides - you lose your benefit and service provider(in this govt) cannot reach you. Every year, nearly 20 lakh crore is disbursed in government schemes in India.

What we’re building - 

An end-to-end AI guide that can help you get your right benefit from government schemes 

**Working explained**:

- finding right scheme for you - conversational AI that takes your input and outputs you right scheme - powered by fine-tuned jugalbandi API
    - eg there will be different sub-models for health, tourism , etc
    - initial focus will be on schemes which can be filled online and are highly neglected but deserving
- filling the form for you - let’s say you find that you are eligible for sports related scheme, it’ll help you apply the scheme by:
    - documents : if you have any documents missing like say fitness or income certificate, it’ll guide you in creating one
    - form-filling: if you’ve all the documents, then it’ll help you apply for the form via AI-assisted onboarding
    - basically it’ll take all the inputs already given in part one and more inputs needed and file the form for you
    - if form can be filled online, it’ll try to use its API to fill the form and submit it. if offline, it’ll give you a post-filled form which you can submit later at your convenience.
        - e.g. using Jan Aushadhi API you can find nearby store details and avail generic medicines.
        - e.g 2, you can apply for a new ration card or modify existing ration card details in Chandigarh using Civil Supplies Dept API. Similarly in dadra and nagar haveli too.
        - eg 3 MSME registration in Tamil Nadu can be fully done by using open API’s
        - eg 4 you can apply for a new water / sewer connection in Haryana
- the above will be powered by AI Onboarding guide which’ll work in both text and voice to help you apply for scheme benefit.
- More importantly, you can ask for help from the AI guide about any field of the form you’re not understanding like say declaring agricultural income for non-irrigated lands(if there’s such a field). At any stage, if you’re stuck, based on its training, it’ll be able to help you out.
- later, you will be able to track the status of your form through the unique ID generated for each scheme form.

**Timelines** - 

- people finding relevant scheme - this’ll require domain specific fine tuning - 1 to 2 Month
- AI Onboarding form for various usage scenarios and directly form filling - will work on integrating government APIs or explore other mechanisms of filing form online just form a conversation - will need 3-4 months
- AI support system to help you in case you’re stuck - will need 2 to 3 month from prototype to testing

At end of it, we’ve built an efficient system to deliver people their rights and benefits they are entitled to. It’ll help a lot of less privileged people get benefits which they otherwise would’ve been deprived of. The billion people of this country deserve a better service delivery so they can too realise their dreams.

The AI guide will help billions of Indians living their life with more dignity and fair opportunities so that we can wipe the last tear from last eye.

If you have any thoughts, connect to me at [luv@peopleplus.ai](mailto:luv@peopleplus.ai) or [https://www.linkedin.com/in/luv-singh-ai](My LinkedIn) 

**Other useful Open APIs **- 

- To get application for Continuation of existing registration for next 1 or 3 years in Karnataka
- Apply for Assam Arundhati Gold Scheme meant to provide monetary support to brides to purchase gold, who belong to economically weaker sections of society.
- Get new power connection in Assam
- Check FIR status or complete registration under Tamil Nadu’s police
