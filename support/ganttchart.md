``` mermaid
gantt
    title SIGN TO SPEECH: AN EMBEDDED DEEP LEARNING VISION SYSTEM FOR REAL TIME SIGN LANGUAGE INTERPRETATION
    dateFormat  DD-MM-YYYY
    axisFormat  %d-%m-%y
    %% excludes weekends

    section Meetings
    Project Selection and Definition              :a1, 26-09-2025, 1d
    Project Research Update                       :a2, 10-10-2025, 1d
    Project Specification Review                  :a3, 17-10-2025, 1d
    Hardware Collection and Development Plan      :a4, 24-10-2025, 1d
    Model Development and Accuracy Deep-Dive      :a5, 12-11-2025, 1d

    section Phase 1 - Project Specification & Literature Review
    Phase 1 Deadline                              :vert, 22-10-2025, 0d
    Abstract                                      :b1, 23-09-2025, 1d
    Background of Project                         :b2, 25-09-2025, 3d
    Literature Review                             :b3, 28-09-2025, 12d
    Theme 1 - BSL Recognition Approaches          :b4, after b2, 3d
    Theme 2 - CV and Gesture Tracking             :b5, after b4, 3d
    Theme 3 - Accessibility Technologies & Context:b6, after b5, 3d
    Theme 4 - Deep Learning in CV Classification  :b7, after b6, 3d
    Research Methodology                          :b8, after b7, 5d
    Conclusion, Appendix, Gantt Chart             :b9, after b8, 5d

    section Phase 2 - Model Development
    Train YOLO11 Hand Keypoints Model             :c1, 01-11-2025, 2d
    Evaluate & Optimise Model                     :c2, after c1, 5d
    Develop OpenCV application                    :c3, after c2, 5d
    Integrate YOLO Model with Translation Pipeline:c4, after c3, 5d

    section Phase 3 - Hardware Deployment & Testing
    Deploy Model to Raspberry Pi 5                :d1, 01-01-2026, 5d
    Edge Performance Testing                      :d2, after d1, 10d
    System Integration & Troubleshooting          :d3, after d2, 10d

    section Phase 4 - Final Report & Presentation
    Documentation & Evaluation Report             :e1, after d3, 15d
    Prototype Demonstration Preparation           :e2, after e1, 7d
    Final Presentation & Submission               :e3, after e2, 1d

```