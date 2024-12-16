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
    <h2>Choral Separation</h2>
    <div class="row mt-3">
        <div class="col-sm">
            <div><strong>Mixture:</strong></div>
            {% include audio.liquid path="assets/audio/SINGERS_MIX.mp3" controls=true %}
        </div>
    </div>
    <div class="row mt-3">
        <div class="col-sm">
            <div><strong>Separated Vocal 1:</strong></div>
            {% include audio.liquid path="assets/audio/SINGER1_SEP.mp3" controls=true %}
        </div>
        <div class="col-sm">
            <div><strong>Reference Vocal 1:</strong></div>
            {% include audio.liquid path="assets/audio/SINGER1_REF.mp3" controls=true %}
        </div>
    </div>
    <div class="row mt-3">
        <div class="col-sm">
            <div><strong>Separated Vocal 2:</strong></div>
            {% include audio.liquid path="assets/audio/SINGER2_SEP.mp3" controls=true %}
        </div>
        <div class="col-sm">
            <div><strong>Reference Vocal 2:</strong></div>
            {% include audio.liquid path="assets/audio/SINGER2_REF.mp3" controls=true %}
        </div>
    </div>
</div>

<div class="row mt-3">
    <h2>Ensemble Separation</h2>
    <div class="row mt-3">
        <div class="col-sm">
            <div><strong>Mixture:</strong></div>
            {% include audio.liquid path="assets/audio/VIOLINS_MIX.mp3" controls=true %}
        </div>
    </div>
    <div class="row mt-3">
        <div class="col-sm">
            <div><strong>Separated Violin 1:</strong></div>
        {% include audio.liquid path="assets/audio/VIOLIN1_SEP.mp3" controls=true %}
        </div>
        <div class="col-sm">
            <div><strong>Reference Violin 1:</strong></div>
            {% include audio.liquid path="assets/audio/VIOLIN1_REF.mp3" controls=true %}
        </div>
    </div>
    <div class="row mt-3">
        <div class="col-sm">
            <div><strong>Separated Violin 2:</strong></div>
            {% include audio.liquid path="assets/audio/VIOLIN2_SEP.mp3" controls=true %}
        </div>
        <div class="col-sm">
            <div><strong>Reference Violin 2:</strong></div>
            {% include audio.liquid path="assets/audio/VIOLIN2_REF.mp3" controls=true %}
        </div>
    </div>
</div>

<div class="row mt-3">
    <h2>Solo Singer Separation</h2>
    <div class="row mt-3">
        <div class="col-sm">
            <div><strong>Mixture:</strong></div>
            {% include audio.liquid path="assets/audio/mix_21b.wav" controls=true %}
        </div>
    </div>
    <div class="row mt-3">
        <div class="col-sm">
            <div><strong>Separated Lead Vocal:</strong></div>
            {% include audio.liquid path="assets/audio/lv_est_21b.wav" controls=true %}
        </div>
        <div class="col-sm">
            <div><strong>Reference Lead Vocal:</strong></div>
            {% include audio.liquid path="assets/audio/lv_ref_21b.wav" controls=true %}
        </div>
    </div>
    <div class="row mt-3">
        <div class="col-sm">
            <div><strong>Separated Backing Vocal:</strong></div>
           {% include audio.liquid path="assets/audio/bv_est_21b.wav" controls=true %}
        </div>
        <div class="col-sm">
            <div><strong>Reference Backing Vocals:</strong></div>
            {% include audio.liquid path="assets/audio/bv_ref_21b.wav" controls=true %}
        </div>
    </div>
</div>
