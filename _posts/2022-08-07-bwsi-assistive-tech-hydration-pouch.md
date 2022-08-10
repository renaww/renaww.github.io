---
layout: post
title:  "BWSI Assistive Technology - The Hydration Pouch"
author: Rena
categories: []
tags: []
image: assets\images\hydration pouch\product image.png
comments: false
---

*July 11 - August 7, 2022*

During the summer of 2022, I was selected to be part of Beaverworks Summer Institute (BWSI), an engineering summer program for high school students hosted by MIT's Lincoln Laboratory. Specifically, I was part of the assistive technology (AT) course, where each of us picked a **co-designer** to design an assistive technology with.

> **CO-DESIGNER:** the end users we worked with to desgin a product for. Their input was especially important throughout the build process, and after each iteration we would go to them for testing and feedback. In that sense, they were more like another designer, hence the name **co-designer**.

Over the course of 4 weeks, we attended lectures, participated in exercises, and learned about the design process as well as what it takes to make assistive technology in the real world. At the culmination of the program, we'd each developed our own piece of AT to make an impact on a real user. The entire creation of my product has been documented below.

# My Co-designer

During this course, I worked with my cousin. She is a minimum data set (MDS) and floor nurse at an assisted living home, managing a floor of 12-14 patients in critical condition, and recently received a  PhD in nursing with research focusing on dementia/alzheimer's care. In my initial interview, I asked her about her own challenges at work, as well as challenges she has obseerved in her residents' daily living. Boiled down, she identified multiple issues and/or potential solutions which have been listed below:

##### Regarding residents
- CULTURAL CLASH: With residents from many different cultural backgrounds, many residents don't enjoy the activities they are currently presented with, which they've never been introduced to until arriving at the nursing home. Especially in those with dementia this clash is more striking, since they tend to enjoy and remember only things from when they were young, base upon original culture.
- CULTURAL BRIDGING: To help with these residents' missing cultural connections, my co-designer suggested a way to bridge these residents with younger generations of the same culture, giving the elderly a form of social connection but also giving the younger generations a mentor in life.
- MEMORY TRACING: While residents with memory loss may not fully comprehend the current situation, part of their memories still reacts to "pleasant events"--memories from earlier in life. Thus, these "pleasant events" are often a good way to stimulate the memories of residents with dementia. Assembling these pictures and memories into one interactive "photobook", accompanied with narration from relatives, may be a way to use tech and help make finding "plesant events" easier.
- TECHNOLOGY GAP: Especially with the rise of tech after COVID, many seniors are finding it harder to connect with others. For example, many of their social events still use telephone as video chat, while more effective in providing connection, is too hard for most residents to use without external assistance.
-  TRANSPORTATION: Without drivers' licenses, getting to and from in-person social events has also been a major issue. Even when residents have arranged public transportation, they are bound to schedules that are not as flexible as they like.
- MEDICATION MANAGEMENT: Many older adults actually move to nursing homes because they are taking a lot of medications, so having a more streamlined solution for this would help them live much more independently.
- ASSISTIVE TECH COST: Many current assistive technologies like dentures and hearing aids are extremely easy to lose. At the same time however, they are very expensive to replace. So, my co-designer brought up the idea of using rapid manufacturing techniques to create these technologies for cheaper, while still maintaining their personalization.

##### Regarding caretakers
- COVID CONTACT TRACING: Currently, if a patient becomes COVID-positive, the patient has to list all their contacts and the nursing home contact-traces that way. However, if there was a way to track the residents' COVID exposure automatically, this would be a huge imporvement on behalf of the nursing home facilitators.
- VACCINATION TRACKING: Due to COVID the vaccination requirements at my co-designer's nursing home have become much stricter. With multiple steps and stages that need to be logged. However there is no efficient system to do so--currently everything is being tracked with an Excel sheet, which cannot handle data from all the residents and employees. So, a more efficient tracking method would be greatly beneficial to smoother hospital administration.
- PRESSURE ULCERS: Since many residents are bed-ridden, they tend to develop pressure ulcers. To prevent these, caretakers currently have to reposition the patient every 2 hours, which adds lots of extra time to the caretakers' schedules. If there was a way to automate this, for example a bed that could reposition itself, this would not only ensure residents get timely repositioning, but also take a load of stress of the caretakers.
- INFECTION TRACKING: Nursing home managers often have to track cross-contamination. If one person gets a disease, nurses will measure what bacteria, tract...etc and watch if anyone else gets the same tract nearby, in which case there is a high probability of contamination. However, currently much of this is up to human judgement and my co-designer mentioned it would be greatly helpful if a computer could help more accurately detect and notify of cross-contamination
- ELECTRONIC MEDICAL RECORDS: The point click care software used for nursing home management was something my co-designer also reflected could be more efficient. Currently, the computers are also mounted on stationary carts, so when administering medication, nurses often have to rush between the room and cart, which greatly reduces the efficiency of their work.

##### Affecting both parties
- HYDRATION: On the patient side, many residents affected by memory loss forget to drink water. Coupled with a weakening sense of thirstiness, residents can often become dehydrated without realizing--in fact my co-designer mentioned numerous cases of patients who came in and simply needed to rehydrate. On the healthcare worker side, she brought up the fact that many of her co-workers and her went entire shifts without drinking water--it was simply too inconvenient, and being faced with an immensly busy schedule time would pass in an instant.

# Problem Selection: Dehydration
After reviewing everything my co-designer brought up, I eventually settled on the final problem: dehydration. Different from all the other issues she'd mentioned, dehydration had impact on both patients and the workers taking care of them. My co-designer told a story of an elderly woman that came into the nursing home, sleepy every day and literally needing to be pinched to wake up. After talking with a doctor however, the issue was simply dehydration--after receiving some IV fluids, she was like a whole other person. In fact, after more research, cases like this were far more common than they appeared to be.

> 37% of older people admitted to the emergency department were dehydrated, and, of these, 62% were still dehydrated 48 hours after admission (El-Sharkawy et al, 2014)

My co-designer also described her personal struggle with remembering to keep hydrated: working night shifts and managing an entire wing, each patient has a strict schedule they need to follow. She begins the shift with wound care and updating patient statuses, before rushing to check diabetic patients' insulin levels and administering their dosage at the exact time during dinner. After another round of nighttime medications, only then does she begin writing patient documentation. This entire process ends well into the night, at around 11pm and with so many moving parts she simply forgets to drink water--even while knowing the negative effects of doing so. Furthermore, with the PPE required, and water bottle being in a separate room from their main station, it is simply inconvenient to get water, also contributing to the caretaker dehydration issue.

So, given that dehydration has become prevalent in both parties: the caretaker and patient, I had an idea:
***How could I leverage technology to create a solution that reminds <ins>both</ins> caretakers and patients to stay hydrated?***

With that, I set out to develop a single solution that could solve a problem for both parties...

# Idea Generation
