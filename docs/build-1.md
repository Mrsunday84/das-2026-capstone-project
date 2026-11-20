## Build 1 - My Entry

### What I ran
- npm run demo
- npm run benchmark

### What I saw
- Demo: Ada cancels, Seats left: 2, Next on waitlist: Chidi, quantity 2
- Benchmark: Array.find 492.92 ms for 500 lookups, Map.get 0.41 ms for 500 lookups
- Map was about 1,210x faster

### What I learned
- Array.find is O(n) - it grows when bookings grow because it checks one by one.
- Map.get is O(1) - it stays flat because it jumps straight to the booking by reference code.
- Build 1 is the domain core: the rules of booking, running in the terminal. No website, API or database yet.
