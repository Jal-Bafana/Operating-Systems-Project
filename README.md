# Operating-Systems-Project

# Improving Banker's Algorithm  

## Authors  
**Jal Bafana (K005)** | **Prakhar Mehta (K037)**  
**Subject:** Operating Systems  
**Submission Date:** 31.03.2025  

## Overview  
This project enhances the **Banker’s Algorithm**, a deadlock avoidance method, by addressing its limitations in deadlock detection and resolution. Our improvements ensure better resource allocation handling in real-world systems.  

## Key Enhancements  
- **Deadlock Detection:** Identifies processes stuck in a deadlock.  
- **Deadlock Resolution:** Automatically preempts a process to resolve deadlocks.  
- **Process Preemption:** Removes the first deadlocked process and retries execution.  
- **Optimized Need Matrix Calculation:** Improved efficiency using list comprehensions.  
- **Index Tracking:** Maintains process indices to prevent incorrect shifts.  

## Implementation  
We implemented:  
1. **Original Algorithm** – Based on an existing research paper.  
2. **Improved Algorithm** – Includes deadlock detection and process preemption.  

### Experimental Results  
| Test Case | Deadlocked Processes | Preempted Process | New Safe Sequence |  
|-----------|----------------------|-------------------|--------------------|  
| Case 1    | [0, 2, 4]            | 0                 | [1, 2, 3]          |  
| Case 2    | [1, 3]               | 1                 | [2, 0, 3]          |  

## Challenges Faced  
- **Index shifts when removing processes.**  
- **Ensuring termination after preemption.**  
- **Maintaining efficiency for large process sets.**  

## Conclusion  
Our improvements make the Banker's Algorithm more **practical and reliable** by enabling dynamic deadlock handling.  

📄 **For detailed explanation and code, refer to our paper.**  
