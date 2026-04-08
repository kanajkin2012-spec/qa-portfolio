# 📋 Smoke Checklist: API Testing
## ✅ Critical API Checks

- [ ] GET request returns 200 OK
- [ ] POST with valid data returns 201/200
- [ ] POST with empty required field returns 400
- [ ] Invalid endpoint returns 404
- [ ] Request without auth returns 401
- [ ] Response time < 2 seconds
- [ ] Response contains expected JSON fields

---

## 🔍 Response Validation

- [ ] Status code matches expectation
- [ ] Response body is valid JSON
- [ ] Error messages are descriptive
- [ ] No sensitive data in response

---

