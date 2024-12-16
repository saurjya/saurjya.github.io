---
layout: page
title: Audio Examples 🔊
permalink: /projects/
description: 
nav: true
nav_order: 3
---

This page presents audio examples for my various projects: **Choral Separation**, **Ensemble Separation**, and **Lead Singer Separation**. The audio files presented are from models I've trained during my PhD and PostDoc research.

<div class="row mt-3">
    <h2>Choral Music Separation</h2>
    <div class="col-sm mt-3">
        <div><strong>Mixture:</strong></div>
        {% include audio.liquid path="assets/audio/SINGERS_MIX.mp3" controls=true %}
    </div>
    <div class="col-sm mt-3">
        <div><strong>Separated Source 1:</strong></div>
        {% include audio.liquid path="assets/audio/SINGER1_SEP.mp3" controls=true %}
        <div><strong>Separated Source 2:</strong></div>
        {% include audio.liquid path="assets/audio/SINGER2_SEP.mp3" controls=true %}
    </div>
    <div class="col-sm mt-3">
        <div><strong>Reference Source 1:</strong></div>
        {% include audio.liquid path="assets/audio/SINGER1_REF.mp3" controls=true %}
        <div><strong>Reference Source 2:</strong></div>
        {% include audio.liquid path="assets/audio/SINGER2_REF.mp3" controls=true %}
    </div>
</div>

<div class="row mt-3">
    <h2>Chamber Ensemble Separation</h2>
    <div class="col-sm mt-3">
        <div><strong>Mixture:</strong></div>
        {% include audio.liquid path="assets/audio/VIOLINS_MIX.mp3" controls=true %}
    </div>
    <div class="col-sm mt-3">
        <div><strong>Separated Source 1:</strong></div>
        {% include audio.liquid path="assets/audio/VIOLIN1_SEP.mp3" controls=true %}
        <div><strong>Separated Source 2:</strong></div>
        {% include audio.liquid path="assets/audio/VIOLIN2_SEP.mp3" controls=true %}
    </div>
    <div class="col-sm mt-3">
        <div><strong>Reference Source 1:</strong></div>
        {% include audio.liquid path="assets/audio/VIOLIN1_REF.mp3" controls=true %}
        <div><strong>Reference Source 2:</strong></div>
        {% include audio.liquid path="assets/audio/VIOLIN2_REF.mp3" controls=true %}
    </div>
</div>

<div class="row mt-3">
    <h2>Lead and Backing Vocals Separation</h2>
    <div class="col-sm mt-3">
        <div><strong>Mixture:</strong></div>
        {% include audio.liquid path="assets/audio/mix_21b.wav" controls=true %}
    </div>
    <div class="col-sm mt-3">
        <div><strong>Lead Separated:</strong></div>
        {% include audio.liquid path="assets/audio/lv_est_21b.wav" controls=true %}
        <div><strong>Lead Reference:</strong></div>
        {% include audio.liquid path="assets/audio/lv_ref_21b.wav" controls=true %}
    </div>
    <div class="col-sm mt-3">
        <div><strong>Backing Separated:</strong></div>
        {% include audio.liquid path="assets/audio/bv_est_21b.wav" controls=true %}
        <div><strong>Backing Reference:</strong></div>
        {% include audio.liquid path="assets/audio/bv_ref_21b.wav" controls=true %}
    </div>
</div>


