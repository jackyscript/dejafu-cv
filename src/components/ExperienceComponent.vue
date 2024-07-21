<script setup>
import ExperienceItem from './items/ExperienceItem.vue'
</script>

<template>
  <ExperienceItem>
    <template #company>
      SRP ‑ Systementwicklung für Raumbezogene Planung GmbH (fmly Gesellschaft für Stadt‑ und
      Regionalplanung mbH)
    </template>
    <template #location>Berlin</template>
    <template #position> Software Developer </template>
    <template #date>since Oct. 2016</template>
    <ul>
      <li>
        Continue developing the FIS‑Broker, guiding the technical and operational project
        development after becoming project lead, act as main point of contact regarding further
        development and maintenance of the application.
      </li>
      <li>
        Developed a REST‑API for the FIS‑Broker, enabling the integration of externally developed
        applications.
      </li>
      <li>
        Continued development of the desktop application "METEOR" (Metadateneditor). Enhanced and
        ensured the metadata conformity of Berlin GDI‑DE according to the document "Architektur der
        Geodateninfrastruktur Deutschland ‑ Konventionen zu Metadaten." Improved the UI to provide
        and ensure a more readable appearance and increased functional user experience for visually
        impaired users, who are using larger display settings.
      </li>
      <li>
        Conducted tranings for "METEOR", conveying basic knowledge about metadata creation,
        presentation of new developed features.
      </li>
      <li>
        Developed a system to support decision making in the field of urban planning by creating a
        digital representation of Berlin, which collects heterogeneous data in SQL und NoSQL
        databases and interconnected those meaningfully for stakeholders using a graph database,
        enriched the graph using data from the Wikidata SPARQL query service, built an SPA client to
        enable retrieval and presentation of the data.
      </li>
      <li>Developing and maintaining an application to improve in‑house workflows.</li>
      <li>
        Developing a web application for capturing and monitoring data about endangered plant
        species in Berlin and to highlight which protective measures for which plant should be
        prioritized.
      </li>
      <li>
        Continue developing a web application (the digital representation of the
        Kompensationsflächenregister Berlin), improving the domain‑related workflows by coordinating
        and subsequent implementation of the requested features.
      </li>
      <li>
        Developed an import application, to enable data import of "Kompensationsflächen" by external
        users.
      </li>
      <li>
        Developing a SaaS hosting solution based on Docker containers to enable autonomous
        management and configuration of software components and geodata by users.
      </li>
      <li>
        Developing a new metadata management system for DUVA, as successor of the currently in
        multiple municipalities in Germany deployed system.
      </li>
    </ul>
  </ExperienceItem>

  <ExperienceItem>
    <template #company>SRP ‑ Gesellschaft für Stadt‑ und Regionalplanung mbH </template>
    <template #location>Berlin</template>
    <template #position> Working Student Application Development </template>
    <template #date>Sep. 2016 ‑ Oct. 2016</template>
    <ul>
      <li>Extended the FIS‑Broker system by an archive feature for datasets.</li>
      <li>
        Created a feature to enable user defined configuration of archived and non‑archived
        datasets.
      </li>
    </ul>
  </ExperienceItem>

  <ExperienceItem>
    <template #company>GoLocal GmbH & Co. KG</template>
    <template #location>Munich</template>
    <template #position> Working Student Test Automation </template>
    <template #date>Aug. 2015 ‑ Dec. 2015</template>
    <ul>
      <li>
        Designed and developed automatic UI tests for the main product of the company and set up a
        test suite using the selenium framework.
      </li>
      <li>
        Worked on knowledge transfer for team members, presented a comparison of two side by side
        placed video recordings of tests done manually and automatically by the test suite in the
        final project review, showcasing the latter tests are reducing test time, consistent in
        their execution and more complete.
      </li>
    </ul>
  </ExperienceItem>

  <ExperienceItem>
    <template #company>Chair of Geoinformatics, Technical University of Munich</template>
    <template #location>Munich</template>
    <template #position> Tutor Java Programming </template>
    <template #date>Apr. 2015 ‑ Aug. 2015</template>
    <ul>
      <li>
        Taught students programming using the Java language in the following topics: Implement
        linked lists, B‑trees, heaps and the Dijkstra algorithm, develop a chat program using
        sockets and process XML files using the JDOM library.
      </li>
      <li>Assisted and mentored the students in tutorials.</li>
    </ul>
  </ExperienceItem>

  <ExperienceItem>
    <template #company
      >Institute of Astronomical and Physical Geodesy, Technical University of Munich</template
    >
    <template #location>Munich</template>
    <template #position> Tutor Global Geodetic Observation System and GNSS </template>
    <template #date>Nov. 2013 ‑ Mar. 2015</template>
    <ul>
      <li>
        Created and conducted practical tutorial lessons: Computing and modeling GRACE satellite
        data using the example of ice mass changes of greenland using MATLAB and Python/NumPy.
      </li>
      <li>Revised tutorial assignments, provided feedback to students and lecturers.</li>
    </ul>
  </ExperienceItem>
  <ExperienceItem>
    <template #company>Chair of Remote Sensing Technology, Technical University of Munich</template>
    <template #location>Munich</template>
    <template #position> Tutor Image Understanding </template>
    <template #date>Oct. 2014 ‑ Mar 2015</template>
    <ul>
      <li>
        Conducted practical tutorial lessons in addition to the lectures, provided introductory
        lessons for students about algorithms for feature detection in orthoimagery using
        HALCON/HDevelop.
      </li>
      <li>Revised tutorial assignments, provided feedback to students and lecturers.</li>
    </ul>
  </ExperienceItem>
  <ExperienceItem>
    <template #company>Chair of Geoinformatics, Technical University of Munich</template>
    <template #location>Munich</template>
    <template #position> Research Assistant </template>
    <template #date>Feb. 2014 ‑ Aug. 2014</template>
    <ul>
      <li>
        Participated on creating a process chain to convert a AutoCAD 3D model of the TUM to a
        IndoorGML format based one in the context of a thesis of a Ph.D student.
      </li>
      <li>Supported on preprocessing the AutoCAD 3D model to enable transformation to CityGML.</li>
    </ul>
  </ExperienceItem>
  <ExperienceItem>
    <template #company>Chair of Geoinformatics, Technical University of Munich</template>
    <template #location>Munich</template>
    <template #position> Tutor Geoinformatics </template>
    <template #date>Jun. 2013 ‑ Feb. 2014</template>
    <ul>
      <li>
        Created tutorial lessons for students to learn using ArcGIS for the topics of 3D modeling of
        a city model of Munich, visualization and interpolation of particulate matter data published
        by the UBA (Umweltbundesamt).
      </li>
      <li>Conducted the tutorial lessons, advised the students during their assignments.</li>
    </ul>
  </ExperienceItem>
</template>
