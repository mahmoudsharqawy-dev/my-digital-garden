---
{"dg-publish":true,"permalink":"/osi/protocol/transport-protocol/","dg-note-properties":{}}
---


|                     | TCP (Transmission control Protocol) | UDP (user datagram Protocol) |
| ------------------- | ----------------------------------- | ---------------------------- |
| Speed               | Slower                              | Faster                       |
| Reliability         | Reliable                            | Unreliable                   |
| Segmentation        | Yes                                 | No                           |
| Sequencing          | Yes                                 | No                           |
| reordering(بيرتب)   | Yes                                 | No                           |
| reassembling(بيجمع) | Yes                                 | No                           |
| Acknowledge         | Yes                                 | No                           |
| retransmit          | Yes                                 | No                           |
| connection          | connection_oriented                 | connectionless               |

Segmentation:-
- تقسيم ال message الي اجزاء اصغر لما تكون حجم الرساله كبير
- ساعد في عمليه ال Multiplexing
Sequencing:- اعطي كل جزء رقم لاعاده ترتيبهم عند الاستلام
retransmit:- اعاده ارسال اي رساله فشل وصولها بعد فتره زمنيه معينه
connection_oriented:- قبل ما يبعت اي حاجه بيتاكد من ال DST و يفتح معاه session