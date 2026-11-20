Esta app es para explorar cómo las palabras que usas en tu prompt cambian las posibles respuestas de un Modelo de Lenguaje de Gran Escala (LLM).

Empezamos con un prompt específico pero abierto.

```markdown
Escribe un breve rap sobre tucanes
```

Intenta reemplazar `tucanes` con `peces`.

```markdown
Escribe un breve rap sobre pecces.
```

¿Cómo cambia eso la respuesta del LLM?
Intenta agregar adjetivos u otros modificadores para ver cómo afectan el resultado.

***

## Otras ideas de prompts para explorar

Prueba estos ejemplos para explorar cómo los LLMs navegan entre la certeza y la ambigüedad según el contexto disponible.

### Ejemplos de alta ambigüedad

- "El banco..." (entidad financiera or la orilla del río?)
- "Necesito una receta para mi..." (muchas posibilidades médicas)
- "Por favor pasa el..." (innumerables objetos podrían seguir)
- "El médico examinó al paciente..." (múltiples partes del cuerpo posibles)

### El contexto cambia la probabilidad

- "Voy al banco a..." (ahora probablemente financiero)
- "Voy al banco a pescar..." (ahora probablemente la orilla del río)

### Probabilidad dirigida por especificidad

- "La capital de Francia es..." (certeza muy alta para "París")
- "El símbolo químico del oro es..." (certeza muy alta para "Au")

