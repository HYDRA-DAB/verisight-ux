# User Flow

## Main Verification Flow

1. Open Application
2. Create/Login to Account
3. Set Up Passkey
4. Start Identity Verification
5. Grant Camera Permission
6. Position Face Inside Guide
7. Face Scan
8. Verification Processing
9. Verification Successful
10. Redirect to Dashboard

---

## Error Flow

### Face Not Detected

Face Scan

↓

Display Error Message

↓

Adjust Position

↓

Retry Verification

---

### Poor Lighting

Face Scan

↓

Display Lighting Warning

↓

Improve Lighting

↓

Retry Verification

---

### Camera Permission Denied

Permission Request

↓

Permission Denied

↓

Display Guidance

↓

Allow Permission from Settings

↓

Continue Verification