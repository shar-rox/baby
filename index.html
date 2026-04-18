 "import React, { useState, useEffect, useRef } from 'react';
import { Button } from '../components/ui/button';
import { Heart, Music, MusicOff, Sparkles } from 'lucide-react';
import confetti from 'canvas-confetti';
import '../styles/HomePage.css';

const HomePage = () => {
  const [showYesResponse, setShowYesResponse] = useState(false);
  const [noButtonPosition, setNoButtonPosition] = useState({ x: 0, y: 0 });
  const [noButtonClicks, setNoButtonClicks] = useState(0);
  const [musicPlaying, setMusicPlaying] = useState(false);
  const audioRef = useRef(null);

  // Floating hearts animation
  useEffect(() => {
    const createFloatingHeart = () => {
      const heart = document.createElement('div');
      heart.className = 'floating-heart';
      heart.innerHTML = '💕';
      heart.style.left = Math.random() * 100 + '%';
      heart.style.animationDuration = (Math.random() * 3 + 4) + 's';
      document.querySelector('.hero-section')?.appendChild(heart);
      
      setTimeout(() => heart.remove(), 7000);
    };

    const interval = setInterval(createFloatingHeart, 800);
    return () => clearInterval(interval);
  }, []);

  const handleYesClick = () => {
    // Confetti explosion
    const duration = 3000;
    const end = Date.now() + duration;

    const colors = ['#FFB6C1', '#FFC0CB', '#FF69B4', '#FFE4E1', '#FFF0F5'];

    (function frame() {
      confetti({
        particleCount: 7,
        angle: 60,
        spread: 55,
        origin: { x: 0 },
        colors: colors
      });
      confetti({
        particleCount: 7,
        angle: 120,
        spread: 55,
        origin: { x: 1 },
        colors: colors
      });

      if (Date.now() < end) {
        requestAnimationFrame(frame);
      }
    }());

    setShowYesResponse(true);
  };

  const handleNoHover = () => {
    // Move the NO button to a random position
    const randomX = Math.random() * 200 - 100;
    const randomY = Math.random() * 200 - 100;
    setNoButtonPosition({ x: randomX, y: randomY });
    setNoButtonClicks(prev => prev + 1);
  };

  const toggleMusic = () => {
    if (audioRef.current) {
      if (musicPlaying) {
        audioRef.current.pause();
      } else {
        audioRef.current.play();
      }
      setMusicPlaying(!musicPlaying);
    }
  };

  // REPLACE THIS URL with your audio file or YouTube embed
  // Option 1: Use a direct audio file URL
  // Option 2: Upload audio file to /public folder and use \"/audio.mp3\"
  const audioSrc = \"\"; // Add your audio source here

  return (
    <div className=\"home-container\">
      {/* Background Music Toggle */}
      <button className=\"music-toggle\" onClick={toggleMusic}>
        {musicPlaying ? <Music className=\"w-5 h-5\" /> : <MusicOff className=\"w-5 h-5\" />}
      </button>

      {/* Hidden audio element */}
      {audioSrc && (
        <audio ref={audioRef} loop>
          <source src={audioSrc} type=\"audio/mpeg\" />
        </audio>
      )}

      {/* HERO SECTION */}
      <section className=\"hero-section\">
        <div className=\"hero-content\">
          <div className=\"sparkle-icon\">✨</div>
          <h1 className=\"hero-title\">Hey my love 💌</h1>
          <p className=\"hero-subtitle\">I made something special just for you…</p>
        </div>
      </section>

      {/* MEMORY SECTION */}
      <section className=\"memory-section\">
        <h2 className=\"section-title\">Our Little Moments 🥺</h2>
        <div className=\"polaroid-grid\">
          {/* PHOTO 1 - REPLACE IMAGE URL BELOW */}
          <div className=\"polaroid-card\">
            <div className=\"polaroid-image\">
              <img 
                src=\"https://images.pexels.com/photos/3767401/pexels-photo-3767401.jpeg?auto=compress&cs=tinysrgb&w=600\" 
                alt=\"memory 1\" 
              />
            </div>
            <p className=\"polaroid-caption\">The day you made me smile like this 🥺</p>
          </div>

          {/* PHOTO 2 - REPLACE IMAGE URL BELOW */}
          <div className=\"polaroid-card\">
            <div className=\"polaroid-image\">
              <img 
                src=\"https://images.pexels.com/photos/4046991/pexels-photo-4046991.jpeg?auto=compress&cs=tinysrgb&w=600\" 
                alt=\"memory 2\" 
              />
            </div>
            <p className=\"polaroid-caption\">My favorite place is wherever you are 💕</p>
          </div>

          {/* PHOTO 3 - REPLACE IMAGE URL BELOW */}
          <div className=\"polaroid-card\">
            <div className=\"polaroid-image\">
              <img 
                src=\"https://images.unsplash.com/photo-1616285720779-9e597265df0c?auto=compress&cs=tinysrgb&w=600\" 
                alt=\"memory 3\" 
              />
            </div>
            <p className=\"polaroid-caption\">You're my safe place 🌸</p>
          </div>
        </div>
      </section>

      {/* LOVE LETTER SECTION */}
      <section className=\"letter-section\">
        <div className=\"letter-container\">
          <div className=\"letter-header\">💌</div>
          <p className=\"letter-text\">
            I don't know how you do it, but you make everything softer, warmer, and brighter. 
            Being with you feels like home, like comfort, like magic. I just really really like you… like a lot.
          </p>
          <div className=\"letter-signature\">— Your person 💗</div>
        </div>
      </section>

      {/* BUILD-UP SECTION */}
      <section className=\"buildup-section\">
        <div className=\"buildup-text\">
          <p className=\"fade-in-text delay-1\">So I was thinking…</p>
          <p className=\"fade-in-text delay-2\">What if we did something special?</p>
          <p className=\"fade-in-text delay-3\">Just you and me…</p>
        </div>
      </section>

      {/* THE QUESTION SECTION */}
      <section className=\"question-section\">
        {!showYesResponse ? (
          <>
            <h2 className=\"question-title\">Will you go on a date with me? 💖</h2>
            <div className=\"button-container\">
              <Button 
                className=\"yes-button\"
                onClick={handleYesClick}
                size=\"lg\"
              >
                YES 💕
              </Button>
              <Button 
                className=\"no-button\"
                variant=\"ghost\"
                size=\"sm\"
                onMouseEnter={handleNoHover}
                style={{
                  transform: translate(${noButtonPosition.x}px, ${noButtonPosition.y}px),
                  transition: 'transform 0.3s ease'
                }}
              >
                {noButtonClicks > 3 ? \"Please? 🥺\" : \"No 🙈\"}
              </Button>
            </div>
          </>
        ) : (
          <div className=\"yes-response\">
            <h2 className=\"response-title\">YAYYYY 💕</h2>
            <p className=\"response-text\">
              I'm so excited!! I'll plan something super cute for us 🥺
            </p>
            <div className=\"date-ideas\">
              <h3 className=\"date-ideas-title\">Get ready for something special…</h3>
              <div className=\"idea-tags\">
                <span className=\"idea-tag\">✨ Something magical</span>
                <span className=\"idea-tag\">🌸 Just us two</span>
                <span className=\"idea-tag\">💕 Full of love</span>
              </div>
            </div>
          </div>
        )}
      </section>

      {/* FOOTER */}
      <footer className=\"footer\">
        <p>Made with all my love 💗</p>
      </footer>

      {/* Sparkle Cursor Trail */}
      <div id=\"cursor-sparkle\"></div>
    </div>
  );
};

export default HomePage;
"
