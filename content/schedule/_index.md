---
title: Schedule
cms_exclude: true

# View.
#   1 = List
#   2 = Compact
#   3 = Card
view: 2

# Optional header image (relative to `static/media/` folder).
header:
  caption: ""
  image: ""
---
<!-- The workshop will be held on **Monday, 26th February, 2024** and all times are in **PST (Pacific Standard Time zone)**. The workshop location is **Room 110** and the poster session will be in **Room 301** from 4-6 PM. -->

The workshop location is **Room: Conference J** at Singapore EXPO, Singapore. 

Each accepted paper will be presented in exactly one of the poster sessions listed below.  Please find your poster session number in this list: [Poster Session Link](https://docs.google.com/spreadsheets/d/1374QMSzLsuYCcw_1TJtqA9eiposTnhqieuex4VLErOA/edit?usp=sharing).

Guidelines about the poster session (including poster size) are provided by the main conference: [Guidelines Link](https://aaai.org/conference/aaai/aaai-26/poster-guidelines/)


<style>
.schedule {
  max-width: 800px;
  margin: 0 auto;
  font-family: system-ui, -apple-system, sans-serif;
}

.schedule-item {
  display: flex;
  gap: 1.5rem;
  padding: 1rem;
  margin: 0.5rem 0;
  border-left: 4px solid #e5e7eb;
  background: white;
  transition: all 0.2s ease;
}

.schedule-item:hover {
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.time {
  min-width: 140px;
  color: #4b5563;
  font-weight: 500;
}

.event {
  flex-grow: 1;
}

.speaker { border-left-color: #3b82f6; }
.poster { border-left-color: #22c55e; }
.break { border-left-color: #f97316; }
.panel { border-left-color: #a855f7; }

.legend {
  display: flex;
  gap: 1.5rem;
  flex-wrap: wrap;
  margin-top: 2rem;
  padding: 1rem;
  font-size: 0.875rem;
}

.legend-item {
  display: flex;
  align-items: center;
  gap: 0.5rem;
}

.legend-dot {
  width: 0.75rem;
  height: 0.75rem;
  border-radius: 50%;
}

.legend-speaker { background: #3b82f6; }
.legend-poster { background: #22c55e; }
.legend-break { background: #f97316; }
.legend-panel { background: #a855f7; }
</style>

<div class="schedule">
  <div class="schedule-item">
    <div class="time">1:15 - 1:20</div>
    <div class="event">Opening Remarks (Jana Doppa and Vipin Kumar)</div>
  </div>

  <div class="schedule-item speaker">
    <div class="time">1:20 - 1:50</div>
    <div class="event">Invited Talk: Shashi Shekhar</div>
  </div>

  <div class="schedule-item break">
    <div class="time">1:50 - 2:30</div>
    <div class="event">Oral Presentations</div>
  </div>

  <div class="schedule-item poster">
    <div class="time">2:30 - 3:00</div>
    <div class="event">Poster Presentations 1</div>
  </div>

  <div class="schedule-item speaker">
    <div class="time">3:00 - 3:30</div>
    <div class="event">Invited Talk: Bryan Kian Hsiang Low</div>
  </div>

  <div class="schedule-item poster">
    <div class="time">3:30 - 4:00</div>
    <div class="event">Poster Presentations 2</div>
  </div>

  <div class="schedule-item speaker">
    <div class="time">4:00 - 4:25</div>
    <div class="event">Invited Talk: Kirti Rajagopalan</div>
  </div>

  <div class="schedule-item poster">
    <div class="time">4:25 - 4:55</div>
    <div class="event">Poster Presentations 3</div>
  </div>

  <div class="schedule-item">
    <div class="time">4:55 - 5:00</div>
    <div class="event">Closing Remarks (Vipin Kumar)</div>
  </div>

  <div class="schedule-item panel">
    <div class="time">5:00 - 6:00</div>
    <div class="event">Joint Panel with AgriAI Workshop</div>
  </div>

  <div class="legend">
    <div class="legend-item">
      <div class="legend-dot legend-speaker"></div>
      <span>Invited Talks</span>
    </div>
    <div class="legend-item">
      <div class="legend-dot legend-poster"></div>
      <span>Poster presentations</span>
    </div>
    <div class="legend-item">
      <div class="legend-dot legend-break"></div>
      <span>Oral Presentations</span>
    </div>
    <div class="legend-item">
      <div class="legend-dot legend-panel"></div>
      <span>Panel Session</span>
    </div>
  </div>
</div>
