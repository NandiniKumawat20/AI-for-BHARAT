# HealthLink AI (SehatSathi) – System Design

## System Overview
HealthLink AI (SehatSathi) is an AI-powered healthcare assistant designed for underserved communities. It helps users understand symptoms, get safe first-aid guidance, identify emergencies, and connect to nearby government hospitals. The system supports multiple family members under one account.

## How the Solution Solves the Problem
1. Symptom Clarity  
   - AI analyzes symptoms  
   - Labels risk as Low / Medium / High  
   - Suggests first aid or hospital visit  

2. Stops Unsafe Treatment  
   - No medicine prescription  
   - Only WHO-based safe first aid  

3. Emergency Detection  
   - Identifies danger signs  
   - Triggers emergency alert  
   - Directs user to nearest hospital  

4. Civil Hospital Access  
   - Finds nearest government hospital  
   - Shows OPD / emergency details  
   - Suggests correct department  

5. Family Care in One App  
   - One account with multiple family profiles  
   - Advice customized by age and risk  

6. Language & Voice Support  
   - Voice and text input  
   - Multiple languages  
   - Simple instructions  

## Architecture (High-Level)
User → Web/Mobile UI → Backend API → AI/NLP Engine →  
Risk Classification → First Aid / Hospital Referral

## Key Modules
- Family Profile Management Module
- Symptom Analysis Module
- Risk Classification Module
- First Aid Guidance Module
- Emergency Detection Module
- Civil Hospital Locator Module

## User Flow
1. User logs in
2. Selects family member profile
3. Enters symptoms (text/voice)
4. AI analyzes symptoms
5. Risk level displayed
6. First aid or hospital referral shown

## Ethical Design
- AI acts as decision-support
- Clear disclaimer shown to users
- Encourages professional medical care
