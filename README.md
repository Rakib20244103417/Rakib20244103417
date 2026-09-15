
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Rakib20244103417 - University Repositories</title>

    <style>
        * {
            box-sizing: border-box;
        }

        html,
        body {
            margin: 0;
            padding: 0;
        }

        body {
            background: #ffffff;
            font-family:
                -apple-system,
                BlinkMacSystemFont,
                "Segoe UI",
                Helvetica,
                Arial,
                sans-serif;
            color: #24292f;
        }

        /* ================================= */
        /* MAIN CONTAINER                    */
        /* ================================= */

        .container {
            width: 100%;
            max-width: 615px;
            margin: 0 auto;
            padding: 0 10px 40px;
        }

        /* ================================= */
        /* UNIVERSITY REPOSITORIES           */
        /* ================================= */

        .repositories {
            width: 100%;
        }

        .repositories h2 {
            margin: 22px 0 10px;
            font-size: 14px;
            font-weight: 600;
            color: #24292f;
        }

        .intro {
            margin: 0 0 16px;
            font-size: 11px;
            line-height: 16px;
            color: #0969da;
        }

        /* ================================= */
        /* MORE REPOSITORIES                 */
        /* ================================= */

        .more-repositories {
            height: 17px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 3px;
            margin-bottom: 4px;
            font-size: 10px;
            color: #24292f;
        }

        .more-repositories span {
            font-size: 8px;
        }

        .more-repositories a {
            color: #24292f;
            text-decoration: none;
        }

        .more-repositories a:hover {
            color: #0969da;
            text-decoration: underline;
        }

        /* ================================= */
        /* REPOSITORY GRID                   */
        /* ================================= */

        .repo-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 4px;
        }

        /* ================================= */
        /* REPOSITORY CARD                   */
        /* ================================= */

        .repo-card {
            position: relative;
            min-height: 99px;
            padding: 11px 15px 30px;

            border: 1px solid #d8dee4;
            border-radius: 5px;
            background: #ffffff;

            text-decoration: none;
            color: #24292f;

            transition:
                border-color 0.15s ease,
                box-shadow 0.15s ease;
        }

        .repo-card:hover {
            border-color: #0969da;
            box-shadow: 0 1px 3px rgba(27, 31, 36, 0.10);
        }

        /* ================================= */
        /* REPOSITORY TITLE                  */
        /* ================================= */

        .repo-title {
            display: flex;
            align-items: center;
            margin-bottom: 7px;

            color: #0969da;
            font-size: 12px;
            line-height: 16px;
        }

        .repo-icon {
            margin-right: 7px;
            font-size: 11px;
            color: #0969da;
        }

        /* ================================= */
        /* DESCRIPTION                      */
        /* ================================= */

        .repo-card p {
            margin: 0;
            color: #24292f;
            font-size: 9px;
            line-height: 12px;
        }

        /* ================================= */
        /* REPOSITORY INFORMATION            */
        /* ================================= */

        .repo-info {
            position: absolute;
            left: 15px;
            bottom: 8px;

            display: flex;
            align-items: center;
            gap: 4px;

            color: #57606a;
            font-size: 9px;
            line-height: 10px;
        }

        /* ================================= */
        /* LANGUAGE DOT                     */
        /* ================================= */

        .dot {
            display: inline-block;
            width: 8px;
            height: 8px;
            border-radius: 50%;
        }

        .java {
            background: #b07219;
        }

        .cpp {
            background: #f34b7d;
        }

        .c {
            background: #555555;
        }

        /* ================================= */
        /* STAR                              */
        /* ================================= */

        .star {
            margin-left: 5px;
            color: #0969da;
            font-size: 15px;
            line-height: 10px;
        }

        /* ================================= */
        /* FORK                              */
        /* ================================= */

        .fork {
            margin-left: 8px;
            color: #0969da;
            font-size: 13px;
        }

        /* ================================= */
        /* FOOTER                            */
        /* ================================= */

        footer {
            margin-top: 25px;
            padding: 15px 0;
            text-align: center;
            border-top: 1px solid #d8dee4;
            font-size: 10px;
        }

        footer a {
            color: #57606a;
            text-decoration: none;
        }

        footer a:hover {
            color: #0969da;
            text-decoration: underline;
        }

        /* ================================= */
        /* MOBILE RESPONSIVE                */
        /* ================================= */

        @media (max-width: 600px) {
            .container {
                width: 100%;
                padding-left: 12px;
                padding-right: 12px;
            }

            .repo-grid {
                grid-template-columns: 1fr;
                gap: 5px;
            }

            .repo-card {
                min-height: 105px;
            }
        }
    </style>
</head>

<body>

<div class="container">

    <!-- ============================= -->
    <!-- UNIVERSITY REPOSITORIES       -->
    <!-- ============================= -->

    <section class="repositories">

        <h2>University Repositories</h2>

        <p class="intro">
            My university coursework archive of course materials,
            assignments and practice.
        </p>

        <!-- More repositories -->

        <div class="more-repositories">
            <span>▼</span>

            <a href="https://github.com/Rakib20244103417?tab=repositories"
               target="_blank"
               rel="noopener noreferrer">
                More repositories here
            </a>
        </div>

        <!-- ============================= -->
        <!-- REPOSITORY GRID                -->
        <!-- ============================= -->

        <div class="repo-grid">

            <!-- CSE 319 -->

            <a href="https://github.com/Rakib20244103417/CSE-319"
               target="_blank"
               rel="noopener noreferrer"
               class="repo-card">

                <div class="repo-title">
                    <span class="repo-icon">▣</span>
                    cse319
                </div>

                <p>
                    Machine Learning from my 7th semester.
                    Instructor: Nasirul Mumenin
                </p>

            </a>


            <!-- CSE 328 -->

            <a href="https://github.com/Rakib20244103417/cse328"
               target="_blank"
               rel="noopener noreferrer"
               class="repo-card">

                <div class="repo-title">
                    <span class="repo-icon">▣</span>
                    cse328
                </div>

                <p>
                    Software Engineering from my 7th semester.
                    Instructor: Nahida Akter Tanjila
                </p>

            </a>


            <!-- MKT 301 -->

            <a href="https://github.com/Rakib20244103417/mkt301"
               target="_blank"
               rel="noopener noreferrer"
               class="repo-card">

                <div class="repo-title">
                    <span class="repo-icon">▣</span>
                    mkt301
                </div>

                <p>
                    Marketing course materials,
                    assignments and practice.
                </p>

            </a>


            <!-- ACT 301 -->

            <a href="https://github.com/Rakib20244103417/act301"
               target="_blank"
               rel="noopener noreferrer"
               class="repo-card">

                <div class="repo-title">
                    <span class="repo-icon">▣</span>
                    act301
                </div>

                <p>
                    Accounting course materials,
                    assignments and practice.
                </p>

            </a>


            <!-- CSE 324 -->

            <a href="https://github.com/Rakib20244103417/cse324"
               target="_blank"
               rel="noopener noreferrer"
               class="repo-card">

                <div class="repo-title">
                    <span class="repo-icon">▣</span>
                    cse324
                </div>

                <p>
                    Course materials and assignments
                    from my 6th semester.
                </p>

            </a>


            <!-- CSE 326 -->

            <a href="https://github.com/Rakib20244103417/cse326"
               target="_blank"
               rel="noopener noreferrer"
               class="repo-card">

                <div class="repo-title">
                    <span class="repo-icon">▣</span>
                    cse326
                </div>

                <p>
                    Course materials, assignments
                    and practice.
                </p>

            </a>


            <!-- CSE 322 -->

            <a href="https://github.com/Rakib20244103417/cse322"
               target="_blank"
               rel="noopener noreferrer"
               class="repo-card">

                <div class="repo-title">
                    <span class="repo-icon">▣</span>
                    cse322
                </div>

                <p>
                    Artificial Intelligence and Expert System Lab
                    from my 6th semester.
                    Instructor: Md. Mamun Hossain
                </p>

            </a>


            <!-- CSE 342 -->

            <a href="https://github.com/Rakib20244103417/cse342"
               target="_blank"
               rel="noopener noreferrer"
               class="repo-card">

                <div class="repo-title">
                    <span class="repo-icon">▣</span>
                    cse342
                </div>

                <p>
                    Java Advanced Programming from my 5th semester.
                    Instructor: Most. Jannatul Ferdous
                </p>

                <div class="repo-info">
                    <span class="dot java"></span>
                    <span>Java</span>

                    <span class="star">☆</span>
                    <span>1</span>
                </div>

            </a>


            <!-- CSE 320 -->

            <a href="https://github.com/Rakib20244103417/cse320"
               target="_blank"
               rel="noopener noreferrer"
               class="repo-card">

                <div class="repo-title">
                    <span class="repo-icon">▣</span>
                    cse320
                </div>

                <p>
                    Computer Networks from my 5th semester.
                    Instructor: Dr. Khandoker Nadir Parvez ||
                    Updated: 12-04-2026
                </p>

                <div class="repo-info">
                    <span class="dot java"></span>
                    <span>Java</span>

                    <span class="star">☆</span>
                    <span>1</span>
                </div>

            </a>


            <!-- CSE 318 -->

            <a href="https://github.com/Rakib20244103417/cse318"
               target="_blank"
               rel="noopener noreferrer"
               class="repo-card">

                <div class="repo-title">
                    <span class="repo-icon">▣</span>
                    cse318
                </div>

                <p>
                    System Analysis and Design from my 5th semester.
                    Instructor: Shampa Banik
                </p>

                <div class="repo-info">
                    <span class="star">☆</span>
                    <span>1</span>
                </div>

            </a>


            <!-- CSE 302 -->

            <a href="https://github.com/Rakib20244103417/cse302"
               target="_blank"
               rel="noopener noreferrer"
               class="repo-card">

                <div class="repo-title">
                    <span class="repo-icon">▣</span>
                    cse302
                </div>

                <p>
                    Technical Writing and Presentation
                    from my 5th semester.
                    Instructor: Sworna Akter
                </p>

                <div class="repo-info">
                    <span class="star">☆</span>
                    <span>1</span>
                </div>

            </a>


            <!-- CSE 210 -->

            <a href="https://github.com/Rakib20244103417/cse210"
               target="_blank"
               rel="noopener noreferrer"
               class="repo-card">

                <div class="repo-title">
                    <span class="repo-icon">▣</span>
                    cse210
                </div>

                <p>
                    Operating System Lab assignments
                    and projects completed during my
                    4th semester.
                </p>

                <div class="repo-info">
                    <span class="dot cpp"></span>
                    <span>C++</span>

                    <span class="star">☆</span>
                    <span>1</span>
                </div>

            </a>


            <!-- CSE 208 -->

            <a href="https://github.com/Rakib20244103417/cse208"
               target="_blank"
               rel="noopener noreferrer"
               class="repo-card">

                <div class="repo-title">
                    <span class="repo-icon">▣</span>
                    cse208
                </div>

                <p>
                    MySQL Database Lab repository
                    from my 4th semester.
                    Instructor: Farha Akter Munmun
                </p>

                <div class="repo-info">
                    <span class="star">☆</span>
                    <span>1</span>
                </div>

            </a>


            <!-- CSE 232 -->

            <a href="https://github.com/Rakib20244103417/cse232"
               target="_blank"
               rel="noopener noreferrer"
               class="repo-card">

                <div class="repo-title">
                    <span class="repo-icon">▣</span>
                    cse232
                </div>

                <p>
                    Here's the Repo for the codes and
                    problems of Algorithms Lab I'll be
                    doing 4th semester.
                </p>

                <div class="repo-info">
                    <span class="dot cpp"></span>
                    <span>C++</span>

                    <span class="star">☆</span>
                    <span>1</span>
                </div>

            </a>


            <!-- CSE 215 -->

            <a href="https://github.com/Rakib20244103417/cse215"
               target="_blank"
               rel="noopener noreferrer"
               class="repo-card">

                <div class="repo-title">
                    <span class="repo-icon">▣</span>
                    cse215
                </div>

                <p>
                    Computer Architecture from my
                    4th semester.
                    Instructor: Nasrin Akter
                </p>

                <div class="repo-info">
                    <span class="star">☆</span>
                    <span>1</span>
                </div>

            </a>


            <!-- CSE 222 -->

            <a href="https://github.com/Rakib20244103417/cse222"
               target="_blank"
               rel="noopener noreferrer"
               class="repo-card">

                <div class="repo-title">
                    <span class="repo-icon">▣</span>
                    cse222
                </div>

                <p>
                    Here's the codes and problems of
                    Data Structure Theory and Lab
                    I'll be doing 3rd semester.
                </p>

                <div class="repo-info">
                    <span class="dot cpp"></span>
                    <span>C++</span>

                    <span class="star">☆</span>
                    <span>1</span>
                </div>

            </a>


            <!-- CSE 111 -->

            <a href="https://github.com/Rakib20244103417/cse111"
               target="_blank"
               rel="noopener noreferrer"
               class="repo-card">

                <div class="repo-title">
                    <span class="repo-icon">▣</span>
                    cse111
                </div>

                <p>
                    Here's C++ programming step by step
                    a complete guide I did in my 2nd semester.
                    [I've included problem set.]
                </p>

                <div class="repo-info">
                    <span class="dot cpp"></span>
                    <span>C++</span>

                    <span class="star">☆</span>
                    <span>1</span>
                </div>

            </a>


            <!-- CSE 101 -->

            <a href="https://github.com/Rakib20244103417/cse101"
               target="_blank"
               rel="noopener noreferrer"
               class="repo-card">

                <div class="repo-title">
                    <span class="repo-icon">▣</span>
                    cse101
                </div>

                <p>
                    My basic C programming practice.
                </p>

                <div class="repo-info">
                    <span class="dot c"></span>
                    <span>C</span>

                    <span class="star">☆</span>
                    <span>1</span>

                    <span class="fork">♧</span>
                    <span>1</span>
                </div>

            </a>

        </div>

    </section>


    <!-- ============================= -->
    <!-- FOOTER                         -->
    <!-- ============================= -->

    <footer>
        <a href="https://github.com/Rakib20244103417"
           target="_blank"
           rel="noopener noreferrer">
            Rakib20244103417
        </a>
    </footer>

</div>

</body>
</html>
```








