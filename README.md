# SNCIC · Panel de gestión

Panel público (solo lectura) de los planes de trabajo del SNCIC — APC Colombia.

- App: https://panel-sncic.streamlit.app
- Archivo principal: `panel_publico.py`
- Los datos se leen de Google Sheets con una cuenta de servicio. Las credenciales
  (`gsheet_id` y `[gcp_service_account]`) van **solo** en *Settings → Secrets* de
  Streamlit Cloud, nunca en este repositorio.
- La app de edición (planes de trabajo) vive en el repositorio privado `sncicapc/sncic-app`.
