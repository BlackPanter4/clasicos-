![PAGANI Q777 EL LAGARTO REVIVED ZZ](doc/pagani_lagarto_q777.jpg)
# Q777 - EL LAGARTO | Kit de Control de Encendido e Inyección
### Tecnología Desarrollada en México x quantum- | Luchanas, Coahuila

> El primer QP Mexicano. Del rescate DINA/RAMIREZ a los clásicos.

Este no es un corta corriente chino. Es la centralita que usamos para el **Corvette C3 EL LAGARTO edición Comandante** - Piel de lagarto verde, motor mexicano.

Ahora disponible como KIT para reconstrucción de autos clásicos.

---

### 🔥 ¿QUÉ HACE EL KIT Q777?

**1. Control de Encendido Inteligente (Corte de Chispa)**
No corta gasolina, corta CHISPA. Si lo prenden sin llave, el motor se ahoga intencionalmente. Moja bujías y no prende ni a empujones. Más seguro que bomba.

**2. Control de Inyección FAST MODE**
Programable en milisegundos por terminal Python.
`500ms FAST MODE` - Veredicto con folio para pruebas de inyección.

**3. Seguridad con Ubicación GPS**
- Si intentan prenderlo sin tu llave Q777 (Bluetooth/RFID), manda alerta:
- 🚨 `Q777 ALERTA: Intento sin llave - Motor AHOGADO`
- 📍 `https://maps.google.com/?q=25.8912,-101.4157` (Luchanas)
- Con folio oficial `VEREDICTO-Q777-XXXX` para tu seguro

**4. Escáner OBD2 16 Pines Integrado**
Lee niveles por CAN Bus (Pin 6 y 14): gasolina, temperatura, aceite, servicio. Todo en tu celular.

### 🛠️ Tecnológia 100% Mexicana

`Bateria 12V (Pin 16) -> LM317 [Regulador 5V] -> ESP32 -> MCP2515 [CAN] -> Relé 30A NC [Chispa] + NEO-6M GPS`

- **LM317:** Fuente de poder, no toca datos. Protege tu chip.
- **ESP32:** Cerebro Q777 hecho en Luchanas.
- **MCP2515 + TJA1050:** Traductor CAN Bus para autos nuevos y viejos.
- **Relé NC:** Normalmente Cerrado. Si falla el módulo, tu auto SÍ prende. No te deja tirado.

