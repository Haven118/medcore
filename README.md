# Trifinity RP EMS AI Assistant 🚑

## What We Built

**Purpose:** Your personal EMS "brain" - learned your SOP, ranks, Wasabi script. Makes instant protocol decisions, validates treatments, generates training, suggests improvements.

**Single file:** `trifinity-ems-ai.html` - Open in any browser (Chrome/Firefox). No server needed.

## How It Works (5 Tools)

### 1. **Quick Decision Support** 🔍
```
Input: "GSW chest unconscious heavy bleeding"
Output: 
Priority: P2 ⚠️
Protocol: IMMEDIATE AMBULANCE - NO scene treatment
Wasabi: Revive + Bandage bleeding
Transport: YES 
Billing: $9k
```
- **Logic:** Scans your description → Matches exact SOP rules (unconscious=fatal GSW=ambulance)

### 2. **Rank Scope Validator** 🎯
```
Rank: Paramedic | Action: "Surgery torso GSW"
Output: ❌ SURGERY DOCTORS ONLY - Call X-Ray
```
- **Logic:** Each rank's allowed/forbidden actions from SOP Section 2

### 3. **Training Scenario Generator** 🎲
```
Output: P1 MCI Gang shootout - 4 GSWs (1 unconscious torso)
Actions: 10-32 backup, START triage, PD Code 4
```
- **Random complex scenes** for Bed Pan Cleaner → Chief training

### 4. **Wasabi Treatment Matrix** 📊
Full lookup:
| Injury | Treatment | Rank | Price |
|--------|-----------|------|-------|
| Bleeding GSW | Suture Kit | Paramedic+ | $5k revive |
| Leg Trauma | Ice Pack + Crutch | All | $8k mobility |
| Torso GSW | Surgery | DOCTOR | $25k |

### 5. **Division Mistake Trainer** 🚨
Shows exact errors by 1st/2nd/Hospital/Trainee (from SOP gaps)

## Daily Use

1. **Scene:** Paste patient status → Instant protocol
2. **Training:** Generate scenarios → Test recruits
3. **Doubt:** Check "Can Paramedic X?" → Yes/No
4. **Billing:** Treatment → Auto price calculation
5. **Improvements:** SOP gaps highlighted

## Your SOP Fully Encoded

- ✅ 3-tier response (1st=assess, 2nd=transport, hospital=treat)
- ✅ Unconscious/GSW torso rules
- ✅ Surgery=Doctors only
- ✅ 10-codes/Priorities
- ✅ Fines/Pricing
- ✅ Rank structure (Foxtrot→Romeo)

**Open trifinity-ems-ai.html → Your EMS just got 10x smarter!** 🚀
