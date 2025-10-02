---
class: text-left
---

# Reality: What We Actually Did

<v-clicks>

- The custom solution approach didn’t perform as expected
- While the library is open source, there are no public docs on solution design/architecture
- The need to integrate existing apps into the new schema further complicated things

</v-clicks>

---


# Deployed Full Solution and Used Tools

<v-clicks>

- Deployed standard Esri solution
- Scripted post-processing tools to:
  - Customize Esri solution
  - Combine the best from the previous and current solution for existing deployments

</v-clicks>

<v-after>

<div style="min-height:calc(65vh - 6rem); display:flex; align-items:top; justify-content:center; padding-top:1rem; box-sizing:border-box;">
  <div style="text-align:center; width:100%; max-width:700px; padding:0 1rem;">
    <img src="/images/post_process_tool.png" alt="Post-Processing Tool Interface" style="max-width:350px; width:80%; height:auto; display:block; margin:0 auto;" />
  </div>
</div>

</v-after>

---

# Experience Builder Editor and Dashboard


- Created custom Experience Builder editor app and dashboard app

<div style="min-height:calc(65vh - 6rem); display:flex; align-items:top; justify-content:center; padding-top:1rem; box-sizing:border-box;">
    <div style="text-align:center; width:100%; max-width:900px; padding:0 1rem;">
        <img src="/images/Editor_App_Editing_Service_Closeup.gif" alt="Editor App" style="max-width:500px; width:80%; height:auto; display:block; margin:0 auto;" />
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

# Data Model Changes

<v-clicks>

- Brought old services to same schema as new solution
  - Required updating data to accommodate domain changes
- Added related table for tracking notifications

</v-clicks>

<v-after>

<div style="min-height:calc(75 - 6rem); display:flex; align-items:top; justify-content:center; padding-top:1rem; box-sizing:border-box;">
    <div style="text-align:center; width:100%; max-width:700px; padding:0 1rem;">
        <img src="/images/code_sample.png" alt="Code Sample" style="max-width:400px; width:80%; height:auto; display:block; margin:0 auto;" />
    </div>
</div>

</v-after>

---

# v4 Transition

<v-clicks>

- For some clients, no transition was needed
- We used a separate process to deploy v4 from scratch

</v-clicks>

<v-after>

<div style="min-height:calc(65vh - 6rem); display:flex; align-items:top; justify-content:center; padding-top:1rem; box-sizing:border-box;">
    <div style="text-align:center; width:100%; max-width:400px; padding:0 1rem;">
        <img src="/images/Post_Processing_Tool_V4.gif" alt="Post Processing V4" style="max-width:350px; width:80%; height:auto; display:block; margin:0 auto;" />
    </div>
</div>

</v-after>

---

# v4 Transition

- For some clients, no transition was needed
- We used a separate process to deploy v4 from scratch
- Still included custom applications and schema modifications



---

# Scale of Deployment

- Deployed 18 new ArcGIS Online organizations
- Onboarded two existing organizations that previously lacked solutions
- Migrated 72 previous organizations to the new solution