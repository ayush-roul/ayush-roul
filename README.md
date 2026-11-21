```sql
-- Database: ayush_roul_db | Role: Incoming Trainee Programmer @ YASH Technologies
SELECT 
    project_id, 
    module_name, 
    core_stack, 
    status 
FROM ayush_roul.portfolio 
WHERE domain IN ('Java', 'SQL', 'IoT') 
ORDER BY project_id ASC;
```

<table>
  <thead>
    <tr>
      <th>project_id</th>
      <th>module_name</th>
      <th>core_stack</th>
      <th>status</th>
      <th>repo</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>01</code></td>
      <td><code>smart_kissan_db</code></td>
      <td><code>PostgreSQL, Supabase, Python, MobileNetV2</code></td>
      <td><code>TOP_50_TRITHON</code></td>
      <td><a href="#"><code>[src]</code></a></td>
    </tr>
    <tr>
      <td><code>02</code></td>
      <td><code>air_gesture_canvas</code></td>
      <td><code>Python, OpenCV, MediaPipe Hands</code></td>
      <td><code>DEPLOYED</code></td>
      <td><a href="#"><code>[src]</code></a></td>
    </tr>
    <tr>
      <td><code>03</code></td>
      <td><code>alpr_gate_controller</code></td>
      <td><code>YOLOv8, OpenCV, Tesseract OCR, RPi 4</code></td>
      <td><code>PROTOTYPE</code></td>
      <td><a href="#"><code>[src]</code></a></td>
    </tr>
    <tr>
      <td><code>04</code></td>
      <td><code>enterprise_backend</code></td>
      <td><code>Java, SQL, OOP, Relational Modeling</code></td>
      <td><code>ACTIVE</code></td>
      <td><a href="#"><code>[src]</code></a></td>
    </tr>
  </tbody>
</table>

<br>

```sql
-- Querying technical skills & external endpoints
SELECT category, values FROM ayush_roul.tech_stack;
```

<table>
  <thead>
    <tr>
      <th>category</th>
      <th>values</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>languages</code></td>
      <td><code>Java, Python, SQL</code></td>
    </tr>
    <tr>
      <td><code>databases</code></td>
      <td><code>PostgreSQL, Supabase, Relational Schema Design</code></td>
    </tr>
    <tr>
      <td><code>vision_and_ml</code></td>
      <td><code>OpenCV, MediaPipe</code></td>
    </tr>
    <tr>
      <td><code>iot_and_tools</code></td>
      <td><code>Raspberry Pi, ESP32, Arduino, Git, Power BI</code></td>
    </tr>
    <tr>
      <td><code>connect</code></td>
      <td>
        💼 <a href="https://www.linkedin.com/in/ayush-roul-611b93302/"><code>LinkedIn</code></a> • 
        📸 <a href="https://www.instagram.com/ayyx.xsh/"><code>Instagram</code></a>
      </td>
    </tr>
  </tbody>
</table>
