# piano
use_bpm 120
use_synth :piano
x = 21
88.times do
  play x
  sleep 0.25
  x = x+1
end
