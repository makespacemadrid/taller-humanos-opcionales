# IA + Automatizaciones  
## Humanos ¿Opcionales?

**Programar en la era de la IA, agentes y sistemas autónomos**

MakeSpace Madrid  
Javier Fernández

---

## 0. Apertura — El contexto

> Hoy se puede programar sin escribir código.

IA generando código  
Automatizaciones por todas partes  
Repositorios que se despliegan solos  

La pregunta no es *si* se puede.  
La pregunta es **qué significa programar ahora**.

---

## Objetivo del taller

- Entender cómo se programa hoy  
- Ver automatizaciones reales  
- Entender qué papel queda al humano  
- Separar hype de ingeniería  

---

## 1. Programar en la era de las automatizaciones

### Antes
- Editor local  
- Compilar a mano  
- Subir a servidor  
- Reiniciar servicios  

### Ahora
- Repos como fuente de verdad  
- Automatismos reaccionando a eventos  
- Infraestructura declarativa  
- IA como colaborador  

> Programar ya no es ejecutar pasos  
> Es diseñar sistemas que ejecutan pasos por ti

---

## 2. Automatizaciones: CI / CD

### CI — Integración continua
Cada cambio se valida automáticamente:
- lint  
- tests  
- build  

### CD — Despliegue continuo
Si pasa CI:
- se publica  
- se despliega  

> Si algo se puede olvidar, debe automatizarse

---

## GitHub Actions como motor

Eventos típicos:
- Pull Request → tests  
- Merge → build  
- Release → deploy  

GitHub Actions = sistema nervioso autónomo del repo

---

## 3. ¿Qué es un agente de programación?

De chatbot a agente:

- Chatbot → responde texto  
- Agente → actúa  

> Un agente es un modelo de IA con permisos

---

## Disección de un agente

Un agente tiene:
- Modelo de IA  
- Objetivo  
- Plan  
- Herramientas  
- Límites  

---

## Herramientas típicas de un agente

- crear_plan  
- leer_fichero  
- modificar_fichero  
- ejecutar_comando  
- clonar_repositorio  

Ciclo: pensar → actuar → observar → corregir

---

## 4. Del prompt a producción

Flujo completo:

1. Prompt  
2. Agente modifica repo  
3. Confirmación humana  
4. Agente revisor  
5. CI automático  
6. Build de imagen  
7. Deploy automático  

> El humano deja de empujar botones  
> y pasa a validar decisiones

---

## Demo en producción

Servicio web real con Docker, GitHub Actions y Watchtower.

---

## 5. Buenas prácticas

Si vas a trabajar con agentes,  
el código necesita instrucciones tanto como las personas.

---

### El repositorio como contrato

Los agentes no adivinan contexto ni arquitectura.

---

### AGENTS.md

Documento común para cualquier agente.

Incluye:
- propósito  
- reglas  
- estilo  
- qué no hacer  

---

### CLAUDE.md / CODEX.md / QWEN.md

Instrucciones específicas por proveedor.

---

### Otras buenas prácticas

- permisos mínimos  
- entornos aislados  
- revisión humana siempre  

> Un buen prompt empieza antes del prompt

---

## 6. Herramientas, costes, límites y privacidad

Tres categorías:
- de pago  
- tier free  
- auto-albergado  

---

## 7. Peligros y seguridad

Un agente es software con permisos.

Riesgos:
- exfiltración  
- código contaminado  
- envenenamiento  

Mitigaciones:
- sandboxes  
- permisos mínimos  
- entornos aislados  

---

## 8. Dilemas

- ¿Qué pasa si dejamos de practicar?  
- ¿Qué pasa cuando el hype baja?  
- ¿Qué pasa cuando la IA consume IA?  

---

## Cierre — Humanos ¿Opcionales?

Opcionales:
- compilar  
- empaquetar  
- desplegar  

Imprescindibles:
- intención  
- criterio  
- responsabilidad  

> El futuro no es programar menos  
> Es programar sistemas que trabajan contigo
