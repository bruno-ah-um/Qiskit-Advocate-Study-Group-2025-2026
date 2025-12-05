**Recording Link:** https://teams.microsoft.com/l/meetingrecap?driveId=b%21-8Th9JRvJkW5nCDSubo9G7umiDa77zxOiIvUQQRLhGh9Xqz4fXvgRo2K9PArSNtm&driveItemId=01XSTDWN2PCM4YL7ICX5A33ELVBZL2X6OM&sitePath=https%3A%2F%2Fibm-my.sharepoint.com%2F%3Av%3A%2Fp%2Fmuehge_de%2FIQBPEzmF_QK_Qb2RdQ5Xq_nMAbkZbgFWJrnfQpJO3pz4_io&fileUrl=https%3A%2F%2Fibm-my.sharepoint.com%2Fpersonal%2Fmuehge_de_ibm_com%2FDocuments%2FRecordings%2FQiskit%2520Advocate%2520Study%2520Group%25202025%2520%25202026-20251121_150432-Meeting%2520Recording.mp4%3Fweb%3D1&iCalUid=040000008200E00074C5B7101A82E00807E90B1571906798ED39DC010000000000000000100000008D9A833831BD4C43B9508271A865F5A4&masterICalUid=040000008200E00074C5B7101A82E0080000000071906798ED39DC010000000000000000100000008D9A833831BD4C43B9508271A865F5A4&threadId=19%3Ameeting_YWFkOTI5M2ItYTk3OS00ZWEyLTkzMDYtZjNhNzJjNGIzYWQw%40thread.v2&organizerId=9f5ef063-9507-4a55-8329-1c3bded492cd&tenantId=fcf67057-50c9-4ad4-98f3-ffca64add9e9&callId=7ab40354-6550-4941-a46b-9d131c466b30&threadType=Meeting&meetingType=Recurring&subType=RecapSharingLink_RecapCore

Here’s a **concise summary of the meeting**:

***

### **Qiskit Advocate Study Group – Meeting Summary**

**Date:** December 5, 2025  
**Duration:** \~34 minutes  
**Topic:** **Transpilation in Qiskit**

***

#### **Main Points**

1.  **Purpose of Transpilation**
    *   Converts logical quantum circuits into hardware-compatible circuits.
    *   Handles mapping from logical qubits to physical qubits.

2.  **Transpilation Workflow**
    *   Steps include:
        *   Circuit optimization
        *   Gate decomposition
        *   Layout mapping
        *   Routing (using SWAP gates for non-adjacent qubits)
        *   Translation to native gates
        *   Additional optimization

3.  **Challenges**
    *   Mapping and routing are complex optimization problems solved with **stochastic methods**, so results vary between runs.
    *   Limited native gates → decomposition increases circuit depth.

4.  **Demonstrations**
    *   GHZ state transpiled multiple times → circuit depth varies.
    *   Optimization levels (0–3) affect circuit depth and gate count:
        *   Higher levels reduce errors but increase cost and complexity.

5.  **Exam Question Discussion**
    *   Sample question on coupling maps and ancilla qubits.
    *   Correct answer identified as **A**, based on connectivity and SWAP usage.

6.  **Next Steps**
    *   Share notebooks and recording link on GitHub.
    *   Participants to try sample exam and share feedback.
    *   **Next session:** *Execution Modes* on **January 16, 2026**.
    *   Proposal to start next meeting **30 minutes earlier** (2:30 PM).

***

#### **Action Items**

*   Thorsten: Share notebooks and recording.
*   Team: Attempt sample exam before next meeting.
*   Confirm new meeting time and volunteer for next topic.

***

✅ Would you like me to:

*   **Create a one-page summary document for distribution**,
*   **Prepare a slide deck with visuals for the team**, or
*   **Draft a short email update with key points and next steps**?
