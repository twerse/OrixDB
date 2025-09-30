# Twerse Shared-Code Valorized License v1.2 (Draft)

**Copyright © Twerse inc. (51% 9280-4061 Québec inc., 49% Contributor Community)**  

---

## 1. General Preamble
This license governs the **commercial use** of Twerse projects (including OrixDB, RSON implementations, and related tools).  
It enables broad adoption while ensuring **fair value return** to contributors through the Shared-Code model defined in the **Twerse Charter v1.6**.  

This License complements the **Open Shared-Code License v1.1**, which governs non-commercial and internal individual use.  

---

## 2. Definitions
- **“Twerse”**: the entity holding copyright over licensed software and formats.  
- **“Contributor”**: any person whose modifications or improvements are accepted into a Twerse project.  
- **“User”**: any person or organization using the licensed software.  
- **“Commercial Use”**: any use that generates direct or indirect revenue, including hosting, SaaS, resale, integration into products, or organizational internal use beyond individuals/self-employed.  
- **“Per Active Server”**: any server instance (physical, virtual, or cloud) operated by the User **outside of Twerse’s official hosted services**.  

---

## 3. Granted Rights
- Permission to read, modify, and redistribute source code, subject to this license.  
- Commercial use permitted under the licensing tiers defined in Section 5.  
- Users retain freedom for research, prototyping, and testing within their licensed tier.  

---

## 4. User Obligations
- All redistributions must include this license.  
- Modifications must be submitted to Twerse’s official infrastructure to be recognized as contributions.  
- Contributors assign economic rights to Twerse in exchange for access to the **49% collective pool**.  
- Any commercial use must be declared and billed under Twerse’s official infrastructure.  

---

## 5. Commercial Licensing Tiers
1. **Free Use (Shared-Code Open)**  
   - Individuals and self-employed workers.  
   - Free internal use, no commercial redistribution.  
   - Upgrading to a Valorized tier required when serving clients or scaling.  

2. **Startups**  
   - Criteria: annual revenue < $1M, < 10 employees.  
   - Fee: $99/month **per active server**.  
   - Cap: 1M RSON/OrixDB requests per month.  
   - **First year of commercial use is free.**  

3. **SMEs**  
   - Criteria: annual revenue < $50M.  
   - Fee: $999/month **per active server**.  
   - Cap: 50M requests per month.  

4. **Enterprises**  
   - Criteria: annual revenue ≥ $50M or > 50M requests/month.  
   - Fee: $9,999/month per cluster (up to 10 servers).  
   - Extension: +$999/month **per additional server**.  

---

## 6. Restrictions
- Prohibited to offer licensed projects as hosted services (DBaaS, SaaS) without an active Valorized license.  
- Prohibited to redistribute under another name.  
- Prohibited to patent any part of licensed software or formats.  

---

## 7. Governance
- **Twerse inc.** retains responsibility for the official evolution of all projects under this license.  
- Strategic decisions follow the **51% 9280-4061 Québec inc. / 49% Contributor Community** model defined in the Charter.  

---

## 8. Warranty and Liability
All licensed projects are provided **“as is”**, without warranties of any kind.  
Twerse inc. and contributors are not liable for damages resulting from their use.  

---

## 9. Compatibility
This license is inspired by **Elastic License 2.0** and **SSPL**, adapted to the **Twerse Shared-Code model**.  

---

# Annexes

### Annex A – RSON (Rust Serialized Object Notation)
- RSON is the **universal open data format** developed under Twerse.  
- **Commercial Use**: must comply with the tiers in Section 5.  
- Redistributed implementations must include attribution to Twerse.  
- Governance: evolution of the standard is decided under the Twerse Charter v1.6.  

---

### Annex B – OrixDB
- OrixDB is the **reference fractal database engine** of RSON.  
- **Commercial Use**:  
  - Hosting, SaaS, or integration into products requires a Valorized license (Section 5).  
  - Licensing fees apply **per active server**, defined as any server operated by the User outside of Twerse’s hosted services.  
- Restrictions: OrixDB may not be offered “as-a-service” without explicit Twerse licensing.  
- Governance: architecture, updates, and official distributions remain under the authority of **Twerse inc.**, with contributions integrated via the 49% DAO.  

---

## 10. Clarifications
1. **Internal Use Boundary**: Only individuals/self-employed may use under the Open License. All organizational or multi-user use requires this Valorized license.  
2. **Detection and Enforcement**: Twerse may enforce compliance through automated monitoring and service interruption. Non-compliance results in suspension until licensing obligations are met.  
3. **Subsidiaries and Affiliates**: Use by subsidiaries, affiliates, or related entities is considered **external use** and requires licensing under this Valorized License.  
4. **Redistribution**: Public redistribution of forks must remain under this License. Internal modifications not redistributed remain free under the appropriate tier.  
5. **Third-Party Compatibility**: Contributions under incompatible licenses (e.g., GPL-only) are not accepted. Users must ensure compatibility before combining with third-party libraries.  
6. **Authority of Twerse inc.**: In case of doubt regarding classification or tier, **Twerse inc. retains final authority**. Users must comply within 30 days of notification.  

---

## 11. Jurisdiction
This License is governed by the **laws of Québec, Canada**.  
Disputes shall be resolved by **binding arbitration in Montréal**, in French or English.  
In case of conflict, the **Twerse Charter v1.6 prevails**, and acceptance of this License implies **acceptance of the Charter**.  
