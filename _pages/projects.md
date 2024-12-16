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
    <div class="caption">
    These examples are related to the work from the Interspeech 2021 paper "Vocal Harmony Separation using Time-domain Neural Networks". The examples are at a sampling rate 22.05 kHz due to the dataset used.
    </div>
    <div class="row">
        <div class="col-sm-6">
            <div><strong>Mixture:</strong></div>
            {% include audio.liquid path="assets/audio/SINGERS_MIX.mp3" controls=true %}
        </div>
        <div class="col-sm-3">
            <div><strong>Separated Vocal 1:</strong></div>
            {% include audio.liquid path="assets/audio/SINGER1_SEP.mp3" controls=true %}
            <div><strong>Reference Vocal 1:</strong></div>
            {% include audio.liquid path="assets/audio/SINGER1_REF.mp3" controls=true %}
        </div>
        <div class="col-sm-3">
             <div><strong>Separated Vocal 2:</strong></div>
            {% include audio.liquid path="assets/audio/SINGER2_SEP.mp3" controls=true %}
             <div><strong>Reference Vocal 2:</strong></div>
            {% include audio.liquid path="assets/audio/SINGER2_REF.mp3" controls=true %}
        </div>
    </div>
</div>

<div class="row mt-3">
    <h2>Ensemble Separation</h2>
    <div class="caption">
    These examples are related to the work from the IEEE WASPAA 2023 paper "Leveraging Synthetic Data for Improving Chamber Ensemble Separation". The test examples are real recordings from the URMP dataset at a sampling rate 44.1 kHz.
    </div>
    <div class="row">
        <div class="col-sm-6">
            <div><strong>Mixture:</strong></div>
            {% include audio.liquid path="assets/audio/VIOLINS_MIX.mp3" controls=true %}
        </div>
        <div class="col-sm-3">
            <div><strong>Separated Violin 1:</strong></div>
            {% include audio.liquid path="assets/audio/VIOLIN1_SEP.mp3" controls=true %}
            <div><strong>Reference Violin 1:</strong></div>
            {% include audio.liquid path="assets/audio/VIOLIN1_REF.mp3" controls=true %}
        </div>
        <div class="col-sm-3">
            <div><strong>Separated Violin 2:</strong></div>
            {% include audio.liquid path="assets/audio/VIOLIN2_SEP.mp3" controls=true %}
            <div><strong>Reference Violin 2:</strong></div>
            {% include audio.liquid path="assets/audio/VIOLIN2_REF.mp3" controls=true %}
        </div>
    </div>
</div>

<div class="row mt-3">
    <h2>Lead Singer Separation</h2>
    <div class="caption">
    These examples are related to my work in collaboration with AudioStrip during my postdoc. This example highlights how lead vocal separation works, where you can listen that the lead vocalist swaps in the prediction for a single phoneme, as one of the backing vocalists temporarily becomes louder than the lead singer.
    </div>
    <div class="row">
        <div class="col-sm-6">
            <div><strong>Mixture:</strong></div>
            {% include audio.liquid path="assets/audio/mix_21b.wav" controls=true %}
        </div>
        <div class="col-sm-3">
            <div><strong>Separated Lead Vocal:</strong></div>
            {% include audio.liquid path="assets/audio/lv_est_21b.wav" controls=true %}
            <div><strong>Reference Lead Vocal:</strong></div>
            {% include audio.liquid path="assets/audio/lv_ref_21b.wav" controls=true %}
        </div>
        <div class="col-sm-3">
            <div class="col-sm">
            <div><strong>Separated Backing Vocals:</strong></div>
           {% include audio.liquid path="assets/audio/bv_est_21b.wav" controls=true %}
            <div><strong>Reference Backing Vocals:</strong></div>
            {% include audio.liquid path="assets/audio/bv_ref_21b.wav" controls=true %}
        </div>
    </div>
</div>
