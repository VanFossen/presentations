---
marp: true
footer: Rich Communication Services (RCS)
_footer: "Nick VanFossen"
theme: gaia
_class:
  - lead
paginate: true
---

# Rich Communication Services

UUG Lightning Talks - Fall 2023

---

## Short Message/Messaging Service (SMS)

- Standardized in 1986

- Various implementations

  - 160 alphanumeric characters (7-bit)
  
    - 140 (8-bit) and 70 (16-bit)

  - 1120 bits

---

## Multimedia Messaging Service (MMS)

- First commercial use in 2002

- File sizes vary per carrier

  - 1600 alphanumeric characters (7-bit)

  - 1.2MB for images

  - 3.5MB for videos

- Discontinued in:
  
  - India, Singapore, Switzerland, Germany

---

## Rich Communication Services (RCS)

- Standardized in 2008 (released 2012)

  - IP based

    - User presence
  
    - Typing indicators
  
    - Read receipts
  
    - Location sharing
  
    - Increased size for photo and video

---

## Universal Profile

- Published in 2016

- Guarantees interconnectivity between carriers

- Cross-Carrier Messaging Initiative (CCMI)

  - AT&T, Sprint, T-Mobile, Verizon

  - Announced in 2019, projected 2020, killed 2021

---

## Google Implementation

- Purchased Jibe in 2015

  - Founded in 2006

- Middleware for RCS

  - Interconnect carrier deployments

    - T-Mobile (2020)

    - AT&T and Verizon (2021)

---

## Google Messages

- Adopted RCS in 2018

  - Rollout in 2020
  
  - On by default in August 2023

- End-to-end encryption

  - Signal Protocol

    - One-to-one (2021), Group (2022)

    - On by default in August 2023

---

## Apples Announced Adaptation

- Announced November 2023

  - Support in 2024

- Will adopt the RCS Universal Profile

  - Work along iMessage

- Will work with GSMA to improve RCS

  - Improving security

  - Add encryption to the standard

---

## Additional Interoperability Standards

- More Instant Messaging Interoperability ([mimi](https://www.ietf.org/archive/id/draft-ralston-mimi-protocol-01.html))

  - Still in draft

    - Defines formats and conventions

- Messaging Layer Security ([MLS](https://www.rfc-editor.org/rfc/rfc9420.html))

  - Published 2023

    - Key exchange

    - Forward secrecy and post-compromise security

<!-- ---

<style scoped>
  ul {
    font-size: 22px
  }
</style>

## References

- <https://en.wikipedia.org/wiki/SMS>

- <https://www.loc.gov/preservation/digital/formats/fdd/fdd000431.shtml>

- <https://en.wikipedia.org/wiki/Multimedia_Messaging_Service>

- <https://en.wikipedia.org/wiki/Rich_Communication_Services>

- <https://arstechnica.com/gadgets/2021/04/verizon-att-and-t-mobile-kill-their-cross-carrier-rcs-messaging-plans/>

- <https://jibe.google.com/>

- <https://en.wikipedia.org/wiki/Rich_Communication_Services>

- <https://arstechnica.com/gadgets/2018/04/google-gives-up-on-google-allo-hopes-carriers-will-sort-out-rcs-messaging/>

- <https://9to5mac.com/2023/11/16/apple-rcs-coming-to-iphone/> -->
