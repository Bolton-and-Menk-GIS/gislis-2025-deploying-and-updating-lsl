---
class: text-left
---

# Reality: What we actually did

- The custom solution approach didn’t perform as expected
- While the library is open source, there are no public docs on solution design/architecture
- The need to integrate existing apps into the new schema further complicated things

---


# Deployed full solution and used tools

- Deployed standard Esri solution
- Scripted post-processing tools to:
  - Customize Esri solution
  - Combine the best from the previous and current solution for existing deployments
<div style="min-height:calc(65vh - 6rem); display:flex; align-items:top; justify-content:center; padding-top:1rem; box-sizing:border-box;">
  <div style="text-align:center; width:100%; max-width:700px; padding:0 1rem;">
    <img src="/images/post_process_tool.png" alt="Post-Processing Tool Interface" style="max-width:350px; width:80%; height:auto; display:block; margin:0 auto;" />
  </div>
</div>

---

# Experience Builder Editor and Dashboard

- Created custom Experience Builder editor app and dashboard app
- Used script tool to integrate these into deployed solution:
  - Update data sources
  - Configure sharing
  - Deprecate Esri equivalent items
  - Add to solution item and build ArcGIS Online Item Graph relationships
<div style="min-height:calc(65vh - 6rem); display:flex; align-items:top; justify-content:center; padding-top:1rem; box-sizing:border-box;">
    <div style="text-align:center; width:100%; max-width:700px; padding:0 1rem;">
        <img src="/images/apps_tool.png" alt="Add Apps Tool Interface" style="max-width:350px; width:80%; height:auto; display:block; margin:0 auto;" />
    </div>
</div>

---

# Data model changes

- Brought old services to same schema as new solution
  - Required updating data to accommodate domain changes
- Added related table for tracking notifications
<div style="min-height:calc(65vh - 6rem); display:flex; align-items:top; justify-content:center; padding-top:1rem; box-sizing:border-box;">
    <div style="text-align:center; width:100%; max-width:700px; padding:0 1rem;">
        <img src="/images/code_sample.png" alt="Code Sample" style="max-width:350px; width:80%; height:auto; display:block; margin:0 auto;" />
    </div>
</div>



---

# v4 transition

- For some clients, no transition was needed
- We used a separate process to deploy v4 from scratch
- Still included custom applications and schema modifications
<div style="min-height:calc(65vh - 6rem); display:flex; align-items:top; justify-content:center; padding-top:1rem; box-sizing:border-box;">
    <div style="text-align:center; width:100%; max-width:700px; padding:0 1rem;">
        <img src="/images/migration_tool.png" alt="Migration Tool Interface" style="max-width:350px; width:80%; height:auto; display:block; margin:0 auto;" />
    </div>
</div>

---

# Scale of deployment

- Deployed 18 new ArcGIS Online organizations
- Onboarded two existing organizations that previously lacked solutions
- Migrated 72 previous organizations to the new solution