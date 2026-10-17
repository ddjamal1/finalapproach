# Final Approach — Airport Operations prototype

This is a new gameplay prototype rather than an update to the original flight-path game.

## How to play
1. Tap an inbound aircraft, then the runway to clear landing.
2. After the aircraft lands and exits, tap it, then an available gate (green circle).
3. Wait for gate servicing. Once READY appears, tap the aircraft and then the runway to send it to departure.
4. Tap an aircraft and HOLD to stop it, RESUME to release.
5. Use PAUSE and 1×/2× SPEED in the bottom bar.

Score is completed departures; flow percentage declines as delays accumulate. Traffic increases with flights handled. The map uses a connected taxiway graph and automated routing.

## Known prototype limitations
- Single fictional airport, runway, and four gates.
- Arrivals queue at a fixed approach point rather than using full airborne separation logic.
- Taxiway conflict avoidance is rudimentary; this is not a full ground-control simulator.
- Runway occupancy and crossing clearances are not yet fully simulated.
- Touch target size and world scaling need refinement for narrow portrait screens.

## Deploy
Upload `index.html` to the root of your GitHub Pages repository.
