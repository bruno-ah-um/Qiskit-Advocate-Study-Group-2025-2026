**Recording Link:** https://teams.microsoft.com/l/meetingrecap?driveId=b%21-8Th9JRvJkW5nCDSubo9G7umiDa77zxOiIvUQQRLhGh9Xqz4fXvgRo2K9PArSNtm&driveItemId=01XSTDWN6GFX6V6ATTCRF3UQ26QHM2XNUC&sitePath=https%3A%2F%2Fibm-my.sharepoint.com%2F%3Av%3A%2Fp%2Fmuehge_de%2FIQDGLf1fAnMUS7pDXoHZq7aCAeSRHKr5qygQ9XNelZ6m29Y&fileUrl=https%3A%2F%2Fibm-my.sharepoint.com%2Fpersonal%2Fmuehge_de_ibm_com%2FDocuments%2FRecordings%2FQiskit%2520Advocate%2520Study%2520Group%25202025%2520%25202026-20251205_150307-Meeting%2520Recording.mp4%3Fweb%3D1&iCalUid=040000008200E00074C5B7101A82E00807E90C0571906798ED39DC010000000000000000100000008D9A833831BD4C43B9508271A865F5A4&masterICalUid=040000008200E00074C5B7101A82E0080000000071906798ED39DC010000000000000000100000008D9A833831BD4C43B9508271A865F5A4&threadId=19%3Ameeting_YWFkOTI5M2ItYTk3OS00ZWEyLTkzMDYtZjNhNzJjNGIzYWQw%40thread.v2&organizerId=9f5ef063-9507-4a55-8329-1c3bded492cd&tenantId=fcf67057-50c9-4ad4-98f3-ffca64add9e9&callId=d4f425b0-ecc8-43d9-a5ed-d25c13c625e1&threadType=Meeting&meetingType=Recurring&subType=RecapSharingLink_RecapCore


Here’s a **summary of the meeting** based on the transcript:

***

Here’s a **summary of the meeting** based on the document:

***

### **Meeting Summary – Qiskit Advocate Study Group**

**Date:** December 5, 2025  
**Duration:** \~34 minutes  
**Topic:** **Transpilation in Qiskit**

***

#### **Key Discussion Points**

1.  **Introduction to Transpilation**
    *   Transpilation converts a logical quantum circuit into a form that fits the constraints of real quantum hardware.
    *   Logical qubits differ from physical qubits; mapping and optimization are essential.

2.  **Transpilation Stages**
    *   Virtual circuit optimization.
    *   Gate decomposition (e.g., breaking multi-qubit gates into basic gates).
    *   Layout mapping to physical qubits.
    *   Routing on restricted topology (handling non-adjacent qubits using SWAP gates).
    *   Translation to native gates supported by hardware.
    *   Additional optimization steps.

3.  **Challenges**
    *   Mapping and routing are **optimization problems**, often solved using **stochastic methods** → results can vary between runs.
    *   Limited native gates on hardware → complex decomposition (e.g., SWAP or Toffoli gates expand into many basic gates).

4.  **Example Demonstration**
    *   GHZ state circuit transpiled multiple times → circuit depth varies, showing probabilistic nature of optimization.
    *   Visualization of hardware topology and coupling maps.
    *   Impact of optimization levels (0–3) on circuit depth and gate count:
        *   Higher optimization can reduce errors but increases classical computation cost.

5.  **Exam Question Discussion**
    *   Sample question on transpilation and coupling maps.
    *   Correct answer identified as **A**, based on coupling map and ancilla qubit usage.

6.  **Next Steps**
    *   Share notebooks and meeting recording on GitHub.
    *   Encourage participants to try sample exams before next meeting.
    *   **Next session:** *Execution Modes* (January 16, 2026).
    *   Proposal to start next meeting **30 minutes earlier** (2:30 PM instead of 3:00 PM).

***

#### **Action Items**

*   Thorsten to share notebooks and recording link.
*   Participants to attempt sample exam and share feedback.
*   Volunteers needed for next session; otherwise, Thorsten and Wiktor will lead.
*   Confirm new meeting time (2:30 PM).

***

Would you like me to **create a concise one-page summary for distribution**, or **prepare a slide deck with key points and visuals** for your team?
