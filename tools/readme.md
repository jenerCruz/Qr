⚙️ Workflow: validate-workflow.yml
Guárdalo en una carpeta como tools/validate-workflow.yml para que no se ejecute automáticamente.

🧪 ¿Qué hace este flujo?
Se ejecuta manualmente desde la pestaña de Actions → “Run workflow”.
Te pide la ruta del archivo que quieres validar.
Usa yamllint para verificar la sintaxis YAML.
Hace validaciones básicas para asegurarse de que el archivo tenga las claves name, on, y jobs.
🛡️ Cómo evitar que afecte el repo
No lo pongas en .github/workflows/, guárdalo en tools/ o validadores/.
Solo se ejecuta manualmente.
No modifica nada ni publica resultados, solo muestra en el log.
