// 1. Importing the most essential package: Me!
import { Farahani as Dev, Fun as Life } from 'universe';

// 2. Initialize my personality
const mahdi = new Dev({
  name: 'مهدی فراهانی (Mahdi Farahani)',
  title: 'Front-End Engineer ⚡',
  mood: Life.ENJOY_THE_CHAOS,
  powerLevel: 9001,
});

// 3. Let's print my presence to the world
console.log(`
  Hey there 👋, I’m Mahdi!  
  Turning ☕ into UI & bugs into features since... well, never mind.
`);

// 4. My skills (abridged, but spicy)
const skills = [
  'React', 
  'TypeScript',
  'Next.js',
  'Creativity', 
  'Memes',
  'Infinite curiosity'
];

skills.forEach(skill => mahdi.learn(skill));

// 5. Connect with me, don’t be shy!
const social = {
  Email:    'mahtifarahani@gmail.com',
  LinkedIn: 'https://www.linkedin.com/in/mahdi-farahani-2600871b5',
  Telegram: 'https://t.me/mahtifarahani'
};

Object.entries(social).forEach(([platform, url]) => {
  console.log(`🔗 ${platform}: ${url}`);
});

// 6. Want my official brag-sheet? Here you go:
console.log('📝 Resume: https://flowcv.com/resume/j15rcs18p8');

// 7. Easter egg: If you’ve read this far, drop me a “👾” on Telegram!

// 8. Final words
console.log(`
  🚀 Pushing pixels, pixels pushing back.
  🧩 Always building, always learning, always questioning.
  🔮 If you like what you see, let’s build the future.
`);
