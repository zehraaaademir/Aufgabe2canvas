```css
/* Canvas Grid Layout */
.canvas-grid {
  display: grid;
  grid-template-columns: 1fr 2fr 1fr;
  gap: 20px;
  margin-bottom: 40px;
}

.value-grid, .journeys-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 30px;
  margin: 30px 0;
}

/* Core Interaction Styling */
.core-interaction {
  background-color: #f0f9ff;
  padding: 20px;
  border-radius: 10px;
  border: 2px solid #0ea5e9;
}

.interaction-tools, .filters {
  background: white;
  padding: 15px;
  margin-top: 20px;
  border-radius: 8px;
  box-shadow: 0 3px 10px rgba(0,0,0,0.1);
}

/* Typografie */
h3 {
  color: #0f766e;
  border-bottom: 2px solid #14b8a6;
  padding-bottom: 5px;
}

/* Responsive Design */
@media (max-width: 768px) {
  .canvas-grid, .value-grid, .journeys-grid {
    grid-template-columns: 1fr;
  }
}
