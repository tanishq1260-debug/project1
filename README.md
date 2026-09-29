# ShadowOps

## AI-Powered Incident Intelligence with Persistent Organizational Memory

ShadowOps is an AI-powered incident response application that helps teams investigate production incidents using organizational memory.

Instead of treating every incident as a new problem, ShadowOps recalls previous incidents, root causes, successful fixes, and failed approaches to provide more informed investigation and recommendations.

## 🧠 Hindsight Memory

ShadowOps uses Hindsight as its persistent memory layer.

The system can remember:

- Previous incidents
- Root causes
- Resolution steps
- Successful fixes
- Failed approaches
- Operational learnings

When a new incident occurs, ShadowOps searches organizational memory and uses previous experience to help investigate and recommend a resolution.

## 🔄 Learning Loop

New Incident  
↓  
AI Investigation  
↓  
Recall Organizational Memory  
↓  
Recommend Resolution  
↓  
Engineer Resolves Incident  
↓  
Save Resolution to Memory  
↓  
Future Incidents Benefit

## ✨ Features

- AI incident investigation
- Resolution recommendations
- WHY explanation for recommendations
- Organizational memory viewer
- Save incident resolutions back to memory
- Learning from previous incidents

## 🏗️ Technology

- React
- FastAPI
- Python
- Hindsight
- REST API

## 🚀 Running Locally

### Backend

```bash
uvicorn main:app --reload