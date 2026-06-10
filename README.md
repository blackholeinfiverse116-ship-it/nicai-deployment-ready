# REVIEW_PACKET.md

## NICAI Deployment Submission

Deployment Owner: Ankita Prajapati
Frontend Owner: Nikhil
Backend Owner: Sanskar Pandey

Deployment Status: COMPLETED

---

# Public Access URLs

Frontend URL
https://nicai-frontend-8wut.vercel.app/

Backend URL
https://nicai-intelligence-engine-3.onrender.com

Health Endpoint
https://nicai-intelligence-engine-3.onrender.com/health

Dashboard Endpoint
https://nicai-intelligence-engine-3.onrender.com/dashboard

---

# Deployment Summary

Frontend Deployment

* Platform: Vercel
* Build Command: npm run build
* Output Directory: dist
* Status: Deployed

Backend Deployment

* Platform: Render
* Runtime: Python + FastAPI
* Build Command:
  pip install -r requirements.txt

Start Command:
uvicorn main:app --host 0.0.0.0 --port $PORT

Status: Deployed

---

# Frontend–Backend Integration

Environment Variable:

VITE_API_URL=https://nicai-intelligence-engine-3.onrender.com

Validation:

* Frontend accessible publicly
* Backend accessible publicly
* API requests connected
* Runtime verification completed

---

# Validation Checklist

[✓] Frontend loads
[✓] Backend responds
[✓] Public URLs available
[✓] Deployment completed
[✓] Health endpoint exposed
[✓] Dashboard endpoint accessible
[✓] Live demo readiness verified

---

# Evidence Included

1. Vercel deployment screenshot
2. Render deployment screenshot
3. Health endpoint screenshot
4. Dashboard screenshot
5. Frontend loaded screenshot
6. Deployment walkthrough video

---

# Operational Notes

If backend becomes inactive:

* Open Render dashboard
* Trigger service wake-up
* Wait 30–60 seconds

---

# Known Issues

* Initial Render cold start may delay first response.

---

# Rollback Plan

Frontend:
Redeploy previous Vercel deployment.

Backend:
Rollback to previous stable Render deployment.

---


