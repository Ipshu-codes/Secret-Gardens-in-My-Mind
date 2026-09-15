# 🌻 Secret Gardens in My Mind

> An interactive generative garden built with **TouchDesigner**, where flowers grow through an evolving L-system structure.

**Secret Gardens in My Mind** is a visual experiment exploring the connection between interaction, growth, and generative art. The project creates branching plants and blooming flowers using TouchDesigner and L-systems, with the goal of turning simple human interaction into a living digital garden.

## Concept

The idea is simple:

**Touch → Growth → Bloom**

A small interaction should feel like planting something that gradually grows into a flower.

The visual is inspired by the feeling of having a small garden inside your mind — something that grows quietly with attention.

## Built With

* **TouchDesigner** — real-time visual programming and generative graphics
* **L-Systems** — procedural generation of plant branches
* **Geometry / Instancing** — creating and positioning flowers and branches
* **MediaPipe** — planned for hand tracking and interaction

## Current Features

* Procedurally generated branching structures using an **L-system**
* 3D plant/branch geometry
* Flowers generated separately from the branching structure
* Flower placement and scaling relative to the plant
* Real-time rendering using TouchDesigner
* Camera and lighting setup for the final scene

## Planned Interaction

The next stage of the project is to introduce **MediaPipe hand tracking**.

The intended interaction is:

```text
Hand detected
      ↓
Hand / finger position tracked
      ↓
Interaction mapped into TouchDesigner
      ↓
Plant responds
      ↓
Flower blooms 🌻
```

The goal is for the user's hand movement or touch-like gesture to control the growth and blooming of the garden.

### Currently In Progress

* [ ] MediaPipe integration
* [ ] Hand tracking
* [ ] Mapping hand position to the garden
* [ ] Triggering flower growth through interaction
* [ ] Final interaction and visual polish

## Project Structure

The current TouchDesigner network consists of:

* **L-System** — generates the branching plant structure
* **Geometry / Tube setup** — converts the generated structure into visible branches
* **Flower geometry** — creates the flower element
* **Instancing** — places flower elements within the scene
* **Camera** — controls the scene viewpoint
* **Light** — illuminates the generated garden
* **Render** — produces the final visual output

## Visual Direction

The project aims for a dreamy, slightly surreal aesthetic rather than a realistic botanical simulation.

The garden is intended to feel:

* Organic
* Gentle
* Dreamlike
* Interactive
* Procedurally generated

## Future Ideas

Once hand tracking is working, the project can be expanded with:

* Different flowers for different gestures
* Multiple plants growing from different hand positions
* Blooming animations
* Hand gestures controlling growth speed
* Flowers reacting to movement
* More complex L-system structures
* Audio-reactive growth
* A complete interactive installation experience

## Status

**Work in Progress**

The generative plant and flower system is currently being developed in TouchDesigner. **MediaPipe hand tracking and interactive control are the next major components.**

---

### 🌻 Why "Secret Gardens in My Mind"?

The project is based on the idea that thoughts, emotions, and ideas can grow like plants.

A small interaction can become a branch.

A branch can become a flower.

And eventually, a collection of small moments can become a garden.
