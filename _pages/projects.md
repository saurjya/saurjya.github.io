---
layout: page
title: Audio Examples 🔊
permalink: /projects/
description: 
nav: true
nav_order: 3
---

This page presents audio examples for three of my projects: **Choral Separation**, **Ensemble Separation**, and **Lead Singer Separation**. Each project includes audio files demonstrating various aspects of the separation process.

<div class="row mt-3">
    <h2>Choral Separation</h2>
    <div class="col-sm mt-3 mt-md-0">
        <p><strong>Mixture:</strong></p>
        {% include audio.liquid path="assets/audio/SINGERS_MIX.mp3" controls=true %}
        <p><strong>Separated Source 1:</strong></p>
        {% include audio.liquid path="assets/audio/SINGER1_SEP.mp3" controls=true %}
        <p><strong>Separated Source 2:</strong></p>
        {% include audio.liquid path="assets/audio/SINGER1_SEP.mp3" controls=true %}
        <p><strong>Reference Source 1:</strong></p>
        {% include audio.liquid path="assets/audio/SINGER1_REF.mp3" controls=true %}
        <p><strong>Reference Source 2:</strong></p>
        {% include audio.liquid path="assets/audio/SINGER2_REF.mp3" controls=true %}
    </div>
</div>

<div class="row mt-3">
    <h2>Ensemble Separation</h2>
    <div class="col-sm mt-3 mt-md-0">
        <p><strong>Mixture:</strong></p>
        {% include audio.liquid path="assets/audio/VIOLINS_MIX.mp3" controls=true %}
        <p><strong>Separated Source 1:</strong></p>
        {% include audio.liquid path="assets/audio/VIOLIN1_SEP.mp3" controls=true %}
        <p><strong>Separated Source 2:</strong></p>
        {% include audio.liquid path="assets/audio/VIOLIN2_SEP.mp3" controls=true %}
        <p><strong>Reference Source 1:</strong></p>
        {% include audio.liquid path="assets/audio/VIOLIN1_REF.mp3" controls=true %}
        <p><strong>Reference Source 2:</strong></p>
        {% include audio.liquid path="assets/audio/VIOLIN2_REF.mp3" controls=true %}
    </div>
</div>

<div class="row mt-3">
    <h2>Lead and Backing Separation</h2>
    <div class="col-sm mt-3 mt-md-0">
        <p><strong>Mixture:</strong></p>
        {% include audio.liquid path="assets/audio/mix_21b.wav" controls=true %}
        <p><strong>Lead Separated:</strong></p>
        {% include audio.liquid path="assets/audio/lv_est_21b.wav" controls=true %}
        <p><strong>Lead Reference:</strong></p>
        {% include audio.liquid path="assets/audio/lv_ref_21b.wav" controls=true %}
        <p><strong>Backing Separated:</strong></p>
        {% include audio.liquid path="assets/audio/bv_est_21b.wav" controls=true %}
        <p><strong>Backing Reference:</strong></p>
        {% include audio.liquid path="assets/audio/bv_ref_21b.wav" controls=true %}
    </div>
</div>
