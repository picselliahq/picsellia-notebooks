
- [ ] Create a redirect to profile token when no organization_id
- [ ] Add a page on documentation with "custom format"
  - [ ] Train test split 
  - [ ] Label Map



API routes needed: 

  ====== *Model Management*
  - Update model Spec  *PUT /api/v1/deployment"*
  - Update model version *"POST /api/v1/deployment"*
  - Shadow Model *"POST /api/v1/deployment/shadow"*


  ====== *Inference*
  - predict *"POST /api/v1/predict"*
  - healthcheck ? "*GET /api/v1/ping"*

**On_init method**:

  - Check `deployment_id` exists in env var
  - Get `active_model` for deployment id and download it

