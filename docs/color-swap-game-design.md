# Neon Rush - Game Design Document

## Game Overview

**Publisher**: OneMore Studios  
**Platform**: React Native (iOS/Android)  
**Genre**: Endless Runner / Arcade  
**Tagline**: "Race through the neon maze!"  
**Target Audience**: Casual gamers, all ages  
**Development Time**: 2-3 weeks

## Core Gameplay

### Basic Mechanics

- **Ball Movement**: Ball continuously moves upward on screen
- **Color Switching**: Tap anywhere to cycle through available colors
- **Obstacle Avoidance**: Ball must match obstacle color to pass through
- **Objective**: Survive as long as possible, achieve high score

### Controls

- **Single Tap**: Switch ball color (cycles through: Red → Blue → Green → Yellow → Red...)
- **Hold**: (Future feature) Slow down time briefly

## Game Progression

### Difficulty Scaling

1. **Level 1-10**: 2 colors (Red, Blue), slow speed
2. **Level 11-25**: 3 colors (+ Green), medium speed
3. **Level 26-50**: 4 colors (+ Yellow), fast speed
4. **Level 51+**: All colors, very fast, complex patterns

### Obstacle Types

1. **Static Circles**: Basic color-coded circles
2. **Moving Lines**: Horizontal/vertical lines that move
3. **Rotating Shapes**: Squares, triangles that rotate
4. **Pattern Obstacles**: Multiple obstacles in sequence
5. **Boss Obstacles**: Large, complex multi-color obstacles

## Visual Design

### Art Style

- **Neon/Glow Theme**: Bright, vibrant colors with glow effects
- **Particle Effects**: Color trails, explosion effects
- **Background**: Dynamic color-shifting gradient
- **UI**: Clean, minimal with neon accents

### Color Palette

- **Primary Colors**: Red (#FF4444), Blue (#4444FF), Green (#44FF44), Yellow (#FFFF44)
- **Background**: Dark gradient that shifts through color spectrum
- **Accent**: White/Neon for UI elements

## Monetization Strategy

### In-App Purchases

1. **Remove Ads**: $2.99 (one-time)
2. **Premium Pass**: $4.99 (unlocks all skins + exclusive content)
3. **Coin Packs**:
   - 1000 coins - $0.99
   - 5000 coins - $3.99
   - 10000 coins - $6.99

### Ad Integration

1. **Banner Ads**: Bottom of screen (non-intrusive)
2. **Rewarded Video**:
   - Revive after death (1 per game)
   - Double coins after game
   - Free skin unlock
3. **Interstitial**: Between games (every 3-4 games)

### Skins System

- **Ball Skins**: 20+ designs (emoji, glowing orb, mini planet, etc.)
- **Trail Effects**: Different particle trails
- **Background Themes**: Space, ocean, forest, city
- **Unlock Methods**: Coins, achievements, daily rewards

## Technical Requirements

### React Native Dependencies

- **React Native**: Latest stable
- **React Native Reanimated**: For smooth animations
- **React Native Gesture Handler**: For touch controls
- **React Native Vector Icons**: For UI icons
- **React Native AdMob**: For ad integration
- **React Native Async Storage**: For save data
- **React Native Sound**: For audio effects

### Performance Targets

- **FPS**: 60 FPS on mid-range devices
- **Memory**: < 100MB RAM usage
- **Load Time**: < 3 seconds initial load
- **Battery**: Optimized for extended play sessions

## Audio Design

### Sound Effects

- **Color Switch**: Subtle "pop" sound
- **Obstacle Hit**: Soft "bump" sound
- **Perfect Pass**: Satisfying "chime"
- **Game Over**: Brief "fail" sound
- **Achievement**: "ding" sound

### Music

- **Background**: Upbeat electronic/chiptune track
- **Menu**: Calmer ambient track
- **Game Over**: Brief sad melody

## Game Modes

### 1. Classic Mode

- Standard endless gameplay
- Progressive difficulty
- High score tracking

### 2. Daily Challenge

- Unique daily level
- Special rewards
- Leaderboard for daily scores

### 3. Time Attack

- 60-second time limit
- Maximum score possible
- Power-ups available

### 4. Zen Mode

- No ads, no pressure
- Relaxing gameplay
- Unlockable through premium pass

## Achievements System

### Basic Achievements

- **First Steps**: Complete 10 obstacles
- **Color Master**: Switch colors 100 times
- **Survivor**: Survive 60 seconds
- **Perfectionist**: Complete 10 perfect passes in a row

### Advanced Achievements

- **Speed Demon**: Reach level 50
- **Collector**: Unlock 10 skins
- **Daily Warrior**: Complete 7 daily challenges
- **Legend**: Reach 100,000 points

## Social Features

### Leaderboards

- **Global**: All-time high scores
- **Weekly**: Reset every Monday
- **Daily**: Daily challenge scores
- **Friends**: Connect with friends

### Sharing

- **Screenshot**: Share high scores
- **Replay**: Share gameplay clips
- **Achievements**: Share unlocked achievements

## Development Phases

### Phase 1: Core Gameplay (Week 1)

- Basic ball movement and color switching
- Simple obstacle generation
- Basic collision detection
- Score system

### Phase 2: Polish & Effects (Week 2)

- Visual effects and animations
- Sound integration
- UI/UX improvements
- Performance optimization

### Phase 3: Monetization & Features (Week 3)

- Ad integration
- In-app purchases
- Skins system
- Achievements and leaderboards

## Success Metrics

### Key Performance Indicators

- **Retention**: 40% Day 1, 20% Day 7, 10% Day 30
- **Monetization**: $0.50 ARPU (Average Revenue Per User)
- **Engagement**: 3+ sessions per day, 5+ minutes per session
- **Rating**: 4.5+ stars on app stores

### A/B Testing

- **Ad Frequency**: Test different ad placement frequencies
- **Difficulty Curve**: Test different progression speeds
- **Skin Pricing**: Test different coin costs for skins
- **UI Layout**: Test different button placements

## Future Updates

### Version 2.0 Features

- **Multiplayer**: Real-time competitive mode
- **New Game Modes**: Puzzle mode, boss battles
- **Customization**: User-created obstacle patterns
- **Events**: Limited-time special events

### Long-term Vision

- **Franchise**: Expand to other color-based games
- **Cross-platform**: Web version, console ports
- **Community**: User-generated content platform
