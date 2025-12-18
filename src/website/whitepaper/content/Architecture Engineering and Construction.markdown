---
article: true
layout: page
permalink: /whitepaper/Architecture Engineering and Construction/
title: AI in Architecture engineering and construction
---

# AI Adoption in the AEC Sector in New Zealand: A Living Whitepaper

## Introduction
- Scope window: 18 December 2024–18 December 2025. Evidence shows movement from pilots to operational AI in hazard intelligence (flood nowcasting, landslide susceptibility), municipal information access, water network operations, and site safety. National guardrails and funding signals (New Zealand’s AI Strategy; Public Service AI Framework; cross‑agency AI survey; NZIAT AI Research Platform) underpin uptake across councils and infrastructure owners. University research advanced deep‑learning elevation models and ML‑supported post‑earthquake damage classification using NZ datasets; planning research highlights LLM roles in council workflows. (MBIE, 8 Jul 2025; DIA/GCDO, 29 Jan 2025; Digital.govt.nz AI survey, 11 Aug 2025; MBIE/NZIAT, 18 Sep 2025; University of Canterbury JSPSR, 30 Oct 2025; University of Auckland JBE, 1 Aug 2025; Nature Cities perspective, 9 Jun 2025.) ([mbie.govt.nz](https://www.mbie.govt.nz/about/news/artificial-intelligence-strategy-and-business-guidance-now-available?utm_source=openai))

## Policy and Frameworks
- New Zealand’s AI Strategy — “Investing with confidence” (MBIE, published 8 Jul 2025). First national AI strategy; aligns with OECD AI Principles; sets direction for AI adoption across the economy, including public services that shape AEC planning, consenting and infrastructure delivery. ([mbie.govt.nz](https://www.mbie.govt.nz/business-and-employment/economic-growth/digital-policy/new-zealands-ai-strategy-investing-with-confidence?utm_source=openai))
- Public Service AI Framework (DIA/GCDO, last updated 29 Jan 2025). Sets vision, principles and a six‑pillar work programme for lawful, safe, responsible AI across the Public Service; relevant to council and infrastructure workflows touching AEC. ([digital.govt.nz](https://www.digital.govt.nz/standards-and-guidance/technology-and-architecture/artificial-intelligence/public-service-artificial-intelligence-framework?trk=public_post_comment-text&utm_source=openai))
- Responsible AI Guidance for the Public Service: GenAI (DIA/GCDO, 2025). Practical guidance aligned to the OECD AI system lifecycle; complements the Framework. ([digital.govt.nz](https://www.digital.govt.nz/standards-and-guidance/technology-and-architecture/artificial-intelligence/responsible-ai-guidance-for-the-public-service-genai/overview?utm_source=openai))
- Responsible AI guidance for businesses (MBIE, 2025). Voluntary good‑practice guidance to support private‑sector AI adoption. ([mbie.govt.nz](https://www.mbie.govt.nz/business-and-employment/business/support-for-business/responsible-ai-guidance-for-businesses?utm_source=openai))
- Government AI use — Cross‑agency survey 2025 (published 11 Aug 2025). 70 agencies reported 272 AI use cases; 55 operational; modalities include GenAI, NLP and Computer Vision — indicating readiness for AEC‑relevant deployments in councils and infrastructure agencies. ([digital.govt.nz](https://www.digital.govt.nz/dmsdocument/263~full-results-2025-cross-agency-survey-for-artificial-intelligence-ai-use-cases/html?utm_source=openai))
- New Zealand Institute for Advanced Technology (NZIAT) — AI Research Platform (MBIE, 18 Sep 2025). Up to NZ$70m over seven years to seed ambitious, industry‑connected AI research with downstream AEC relevance. ([mbie.govt.nz](https://www.mbie.govt.nz/about/news/new-zealand-institute-for-advanced-technology-launches-major-ai-investment?utm_source=openai))
- Alignment with AI Blueprint for Aotearoa and AI Forum NZ AEC Working Group mandate. The AEC Working Group’s 2025 programme references AI Blueprint workstreams and is developing sector knowledge assets (events, submissions, a developing knowledge hub). ([aiforum.org.nz](https://aiforum.org.nz/our-work/working-groups/architecture-engineering-and-construction-aec-working-group/?utm_source=openai))

## Current News
- Auckland Transport produced an AI‑generated landslide susceptibility layer across ~8,000 km of roads; 12.5 m road‑segment cross‑sections inform forward works and resilience planning (Dec 2025 article). ([insite.ipwea.org](https://insite.ipwea.org/auckland-transport-harnesses-ai-to-build-resilience/?utm_source=openai))
- University of Canterbury published deep‑learning elevation super‑resolution (JSPSR) that improves global DEMs toward near‑LiDAR‑like accuracy — potential inputs for flood and infrastructure planning (30 Oct 2025). ([mdpi.com](https://www.mdpi.com/2072-4292/17/21/3591?utm_source=openai))
- Watercare (Auckland) reported a wastewater overflow prevented in Ōtara after deploying smart sensors paired with AI analytics to learn “normal” behaviour and flag anomalies (3 Sep 2025). ([watercare.co.nz](https://www.watercare.co.nz/home/about-us/latest-news-and-media/watercare-s-smart-sensors-prevent-wastewater-overflow-in-otara?utm_source=openai))
- Earth Sciences New Zealand/NIWA described ML flood‑inundation nowcasting that runs in 1–2 minutes; operationalisation underway for high‑risk locations (Jan–Jul 2025 updates). ([callaghaninnovation.govt.nz](https://www.callaghaninnovation.govt.nz/stories/ai-flood-forecasting-in-real-time/?utm_source=openai))
- Hutt City Council/Downer/RUSH piloted computer‑vision safety on a live coastal pathway project — detecting falls, no‑go intrusions, PPE use, and traffic speed in temporary traffic management (8 May 2025). ([huttcity.govt.nz](https://www.huttcity.govt.nz/people-and-communities/news/2025/ai-driving-safety-changes-at-tupua-horo-nuku?utm_source=openai))
- Auckland Council announced “Ask Auckland Council” — an LLM‑enabled assistant to help residents navigate planning and service information; one of NZ’s larger local‑government AI pilots (27 Feb 2025). ([ourauckland.aucklandcouncil.govt.nz](https://ourauckland.aucklandcouncil.govt.nz/news/2025/02/auckland-council-ai-initiative-to-boost-customer-experience/?utm_source=openai))
- Hutt City Council published an AI register and outlined trials targeting faster LIMs and resource‑consent workflows; public transparency of AI use cases (Nov 2025 page). ([huttcity.govt.nz](https://www.huttcity.govt.nz/council/our-projects/ai-at-council))

## Research Overview
- Industry‑led and applied research (AEC‑relevant)
  - ML flood‑inundation nowcasting: ESNZ/NIWA convolutional neural network predicts hourly inundation maps in ~1–2 minutes; Westport case study cited; pathway to operations. (Callaghan Innovation, 9 Jan 2025; ESNZ/NIWA pages, 2025.) ([callaghaninnovation.govt.nz](https://www.callaghaninnovation.govt.nz/stories/ai-flood-forecasting-in-real-time/?utm_source=openai))
  - Landslide susceptibility at road‑segment scale: Auckland Transport used AI across extensive geospatial inputs to create a GIS risk layer for forward works and resilience planning. (IPWEA Insite, Dec 2025.) ([insite.ipwea.org](https://insite.ipwea.org/auckland-transport-harnesses-ai-to-build-resilience/?utm_source=openai))
  - LLMs for municipal service/navigation: Auckland Council’s pilot applies cloud AI to cross‑site information retrieval at population scale. (OurAuckland, 27 Feb 2025.) ([ourauckland.aucklandcouncil.govt.nz](https://ourauckland.aucklandcouncil.govt.nz/news/2025/02/auckland-council-ai-initiative-to-boost-customer-experience/?utm_source=openai))
- Academic research by NZ universities (AI‑explicit; within window; AEC‑relevant)
  - University of Canterbury: JSPSR deep‑learning for DEM enhancement (Remote Sensing, 30 Oct 2025). ([mdpi.com](https://www.mdpi.com/2072-4292/17/21/3591?utm_source=openai))
  - University of Auckland: ML‑supported rapid classification of post‑earthquake building damage aligned to NZ RBA/DDE protocols (Journal of Building Engineering, 1 Aug 2025). ([sciencedirect.com](https://www.sciencedirect.com/science/article/pii/S2352710225010447?utm_source=openai))
  - University of Waikato: Perspective on LLMs in urban planning (Nature Cities, 9 Jun 2025) with NZ author affiliation and council‑workflow relevance. ([nature.com](https://www.nature.com/articles/s44284-025-00261-7?utm_source=openai))
  - AUT with Massey co‑author: ITcon paper using an LLM‑driven synthesis step to develop a Next‑Gen Digital Project Manager competency model mapped to smart‑construction/digital‑twin requirements (Sep 2025). ([itcon.org](https://www.itcon.org/paper/2025/58?utm_source=openai))
  - Massey University: Review on Generative AI/LLMs in construction education, training and practice (Buildings, 15 Mar 2025). ([mdpi.com](https://www.mdpi.com/2075-5309/15/6/933?utm_source=openai))
- University capability signals (AI‑explicit, AEC‑adjacent)
  - University of Auckland: NZ–US physics‑informed AI digital‑twin programme (Catalyst Fund, NZ$4.5m) with the Oden Institute; strengthens modelling infrastructure with transfer potential to infrastructure systems (18 Sep 2025). ([auckland.ac.nz](https://www.auckland.ac.nz/en/news/2025/09/18/digital-twin-nz-us-collaboration-receives-catalyst-funding.html?utm_source=openai))
  - AUT: GDI 2025 conference (1–3 Dec 2025) featured streams on AI, digital twins and smart cities for the built environment. ([aut.ac.nz](https://www.aut.ac.nz/news/stories/gdi-2025-conference-in-december?utm_source=openai))
  - Massey University: new undergraduate AI major announced (11 Aug 2025), expanding NZ AI talent pipelines relevant to AEC analytics and operations. ([massey.ac.nz](https://www.massey.ac.nz/about/news/new-artificial-intelligence-major-set-to-launch-in-2026/?utm_source=openai))

## Case Studies
1) Road network landslide susceptibility modelling (Auckland Transport, 2025)  
- Context: 2000+ slips in early‑2023 events prompted development of a predictive risk framework.  
- AI method and application: AI applied to geospatial factors to model susceptibility at 12.5 m segments across ~8,000 km; GIS layer to interrogate drivers (slope, drainage, geology) and prioritise works.  
- Observed outcomes: Supports proactive remediation and forward‑works programming; informs resilience and community engagement. (IPWEA Insite, Dec 2025.) ([insite.ipwea.org](https://insite.ipwea.org/auckland-transport-harnesses-ai-to-build-resilience/?utm_source=openai))

2) Elevation super‑resolution for flood and infrastructure planning (University of Canterbury, 2025)  
- Context: Many districts lack affordable LiDAR for detailed terrain modelling.  
- AI method and application: Deep‑learning (JSPSR) enhances global DEMs toward near‑LiDAR‑like bare‑earth accuracy using open satellite data.  
- Observed outcomes: Provides more accurate, lower‑cost elevation inputs for flood‑risk and infrastructure planning where LiDAR is unavailable. (Remote Sensing, 30 Oct 2025.) ([mdpi.com](https://www.mdpi.com/2072-4292/17/21/3591?utm_source=openai))

3) ML flood‑inundation nowcasting (ESNZ/NIWA, 2025)  
- Context: Physical models are often too slow for rapidly evolving flood response.  
- AI method and application: Pre‑trained convolutional neural network generates hourly inundation maps in 1–2 minutes from sea‑level and river‑flow forecasts.  
- Observed outcomes: Reported high accuracy in a Westport case study (~95% inundation‑area accuracy) and a pathway to operationalisation at high‑risk locations. (Callaghan Innovation, 9 Jan 2025; ESNZ/NIWA, 2025.) ([callaghaninnovation.govt.nz](https://www.callaghaninnovation.govt.nz/stories/ai-flood-forecasting-in-real-time/?utm_source=openai))

4) Computer‑vision safety on civil works (Hutt City Council, Downer, RUSH; May 2025)  
- Context: Improving safety on a live coastal pathway/seawall project.  
- AI method and application: ML/computer‑vision cameras detect falls, no‑go intrusions, PPE use, and traffic speed in temporary traffic management.  
- Observed outcomes: Near‑real‑time alerts to augment supervision; privacy controls aligned to NZ guidance. (Hutt City Council news, 8 May 2025.) ([huttcity.govt.nz](https://www.huttcity.govt.nz/people-and-communities/news/2025/ai-driving-safety-changes-at-tupua-horo-nuku?utm_source=openai))

5) Predictive network operations for wastewater (Watercare, Sep 2025)  
- Context: Reducing overflows and enabling condition‑based maintenance across ~9,000 km network.  
- AI method and application: Sensors with AI analytics learn normal behaviour; fusing sensor, weather, tide and groundwater data to flag anomalies.  
- Observed outcomes: Early prevention of an Ōtara overflow; shift from reactive to proactive maintenance underway. (Watercare news, 3 Sep 2025.) ([watercare.co.nz](https://www.watercare.co.nz/home/about-us/latest-news-and-media/watercare-s-smart-sensors-prevent-wastewater-overflow-in-otara?utm_source=openai))

6) LLM assistant for council service navigation (Auckland Council, Feb 2025)  
- Context: ~1.5 million annual calls; fragmented information across group sites.  
- AI method and application: Cloud LLM‑enabled assistant to retrieve and summarise information across council platforms.  
- Observed outcomes: Anticipated lower effort for residents; reusable pattern for other councils; pilot progressing to wider testing. (OurAuckland, 27 Feb 2025.) ([ourauckland.aucklandcouncil.govt.nz](https://ourauckland.aucklandcouncil.govt.nz/news/2025/02/auckland-council-ai-initiative-to-boost-customer-experience/?utm_source=openai))

## Trends and Outlook
- Hazard intelligence embedded into planning inputs. Deep‑learning elevation and ML hazard products (flood, landslide) are moving from trials to operational layers used in resilience planning and forward works. Evidence: JSPSR publication; AT’s AI landslide GIS layer in current use. ([mdpi.com](https://www.mdpi.com/2072-4292/17/21/3591?utm_source=openai))
- Scaling of computer‑vision safety analytics on worksites. Live piloting on traffic‑managed civil projects shows practical event detection and alerting; governance patterns (privacy‑by‑design) documented by councils. ([huttcity.govt.nz](https://www.huttcity.govt.nz/people-and-communities/news/2025/ai-driving-safety-changes-at-tupua-horo-nuku?utm_source=openai))
- Predictive O&M in water utilities. AI‑enabled anomaly detection is informing proactive maintenance and overflow prevention as sensor coverage grows. ([watercare.co.nz](https://www.watercare.co.nz/home/about-us/latest-news-and-media/watercare-s-smart-sensors-prevent-wastewater-overflow-in-otara?utm_source=openai))
- LLMs augment planning and customer interfaces. Councils are piloting AI assistants; NZ research outlines LLM potential for text‑heavy planning workflows and submissions analysis. ([ourauckland.aucklandcouncil.govt.nz](https://ourauckland.aucklandcouncil.govt.nz/news/2025/02/auckland-council-ai-initiative-to-boost-customer-experience/?utm_source=openai))
- Policy guardrails and investment signals mature. National AI Strategy, Public Service AI Framework, cross‑agency survey and NZIAT investment indicate growing operational confidence and capability building. ([mbie.govt.nz](https://www.mbie.govt.nz/business-and-employment/economic-growth/digital-policy/new-zealands-ai-strategy-investing-with-confidence?utm_source=openai))
- Workforce and research pipelines expand. New AI degree pathways and international collaborations (physics‑informed AI digital twins) strengthen local capability relevant to built‑environment modelling and operations. ([massey.ac.nz](https://www.massey.ac.nz/about/news/new-artificial-intelligence-major-set-to-launch-in-2026/?utm_source=openai))
- Evidence limitations. Public documentation on some deployments remains brief (e.g., limited quantitative impact reporting for site‑safety pilots and early municipal LLM assistants); continued publication of validation metrics would strengthen sector learning. ([huttcity.govt.nz](https://www.huttcity.govt.nz/people-and-communities/news/2025/ai-driving-safety-changes-at-tupua-horo-nuku?utm_source=openai))

## Conclusion
- Overall assessment (as at 18 December 2025). NZ’s AEC sector shows tangible, AI‑explicit adoption in geospatial hazard intelligence, flood nowcasting, utility operations, municipal service access, and site safety — supported by national policy frameworks and new research funding. University‑industry links are driving applied research aligned to NZ risk contexts (flood, landslide, earthquakes). Evidence depth varies across use cases, but momentum is clear. ([mdpi.com](https://www.mdpi.com/2072-4292/17/21/3591?utm_source=openai))
- Strategic insights derived from evidence (non‑prescriptive).
  - Operational AI advances fastest where high‑value data and critical risk contexts intersect (hazards, water networks, transport resilience). ([callaghaninnovation.govt.nz](https://www.callaghaninnovation.govt.nz/stories/ai-flood-forecasting-in-real-time/?utm_source=openai))
  - Clear guardrails plus capability funding correlate with uptake in AEC‑adjacent public services. ([digital.govt.nz](https://www.digital.govt.nz/standards-and-guidance/technology-and-architecture/artificial-intelligence/public-service-artificial-intelligence-framework?trk=public_post_comment-text&utm_source=openai))
  - Documented validation, transparent metrics, and privacy‑by‑design approaches are recurring enablers of scale. ([digital.govt.nz](https://www.digital.govt.nz/standards-and-guidance/technology-and-architecture/artificial-intelligence/responsible-ai-guidance-for-the-public-service-genai/overview?utm_source=openai))