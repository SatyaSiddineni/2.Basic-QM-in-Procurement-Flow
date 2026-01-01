Basic QM in Procurement Flow – SAP QM Functional Project


1. Project Overview 

        This project demonstrates the complete Quality Management process integrated with Procurement in SAP.
        It is designed as a portfolio-ready project for SAP QM Functional Consultants to showcase hands-on knowledge in:

            ✔ Master Data Setup
            ✔ Procurement Cycle with QM
            ✔ Inspection Lot Creation
            ✔ Results Recording
            ✔ Usage Decision & Stock Posting
            ✔ Functional Documentation


2. Business Scenario

        A company wants to ensure that all purchased raw materials undergo Quality Inspection before posting to unrestricted stock.
        The SAP QM in Procurement process enables automated inspection during Goods Receipt (GR) and enforces quality control.


3. Process Flow Diagram

        Purchase Order → Goods Receipt → Inspection Lot → Result Recording → Usage Decision → Stock Posting


4. Project Components

        This repository includes:

            A) Functional Process Documentation (PDF)
            
                    Full explanation of the QM procurement cycle
                    
                            ✔ Master data
                            ✔ Procurement flow
                            ✔ Inspection handling
                    
            B) SAP Master Data
            
                    Material Master (MM01/MM02)
                    Vendor Master (XK01/XK02)
                    Info Record with QM Data (ME11)
                    Inspection Type 01 activation
                    Sampling Procedure & MICs
            
            C) Transaction-Level Execution
            
                    ME51N → Purchase Requisition
                    ME21N → Purchase Order
                    MIGO → Goods Receipt (Inspection Lot triggers)
                    QA32 → Inspection lot processing
                    QE51N → Result recording
                    QA11 → Usage decision


5. Skills Demonstrated

        ✔ SAP QM Functional
        ✔ QM–MM Integration
        ✔ Inspection Lot Processing

      
6. Project Structure

        Basic QM in Procurement Flow/
        │
        │── README.md
        │── Test Data/
        │     └── Sample Data.pdf
        │
        └── Documentation/
              └── Basic QM in Procurement process Flow.pdf


🙌 Author

Satyanarayana Siddineni 
SAP Functional Consultant
