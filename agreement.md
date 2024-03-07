# Participation Agreement

By signing as an individual below, you certify your organization's agreement with the following terms and conditions (where "you" means the organization):

1. Fair use

    You will use shared witnesses of other parties only for high-stakes identifiers that need protection from eclipse attacks, not for disposable identifiers or personal identifiers with a lower bar for attestation. Typically, this means the identifiers are multisig or delegated AIDs that operate under strict governance. The intent is that shared capacity is used for shared security guarantees, not for private scaling needs.

    At least 1/3 of the witnesses in any witness pools that you configure to use these shared witnesses will consist of witnesses contributed by you. This means you must contribute 1 witness to configure a 3-witness pool from the shared set, 2 witnesses for a 4-, 5- or 6-witness pool, etc.

2. Service level intentions

    Any witness that you contribute is intended for production use, where new events come from other participants in the sharing arrangement, and queries come from the general public. This does not mean you guarantee perfection to anyone. There is no service level *agreement*. However, you do certify that your intentions and reasonable expectations about it are:

    * It is accessible on a stable URL via the general internet.
    * It will be active 24x7x365, excluding brief maintenance windows.
    * It is monitored, such that downtime will be noticed quickly.
    * It will continuously run the latest public release of KERI witness code from the `main` branch of keripy. When a new release becomes available, best efforts will be made to update within 2 weeks.
    * It is suitably hardened from attack. It has a wisely configured firewall, unused ports and services are disabled, it receives appropriate patches with low latency, the administrators that operate it are vetted and trained, the secrets that guard access to it are well protected, its infrastructure is resistant to denial-of-service, and so forth.
    * Its data is handled appropriately as a permanent and irreplaceable public resource. It is backed up at least once a day. You won't reset the state of the witness in a way that loses data. If a recovery from backup is needed, and you are unable to do the recovery yourself, you are willing to allow other participants in the sharing arrangement to use the backups to recover the data.
    * If you have unexpected struggles meeting these expectations, you will proactively notify the other participants in the sharing arrangement.

3. Publicness and inclusivity

    You acknowledge that your witness is providing a public service. You intend that anyone who is not a malicious actor may query your witnesses, without regard to their location, their affiliation, their demographics, and so forth.

4. Enforcement

    The enforcement mechanism for this agreement is reputation-based rather than legal. Compliance or non-compliance with this agreement will naturally influence reputation in the community, and it is via reputation that parties are held accountable. You explicitly disclaim any right to sue other participants about their compliance with this sharing arrangement.

5. Proactive monitoring

    You will monitor the evolution of this document, and withdraw your signature if it changes in a way that alters your willingness to agree.

## Signers

The validity of signatures here may be verified by examining the git commit history of this file. 

name | github handle | representing org | date
--- | --- | --- | ---
Daniel Hardman | dhh1128 | Provenant, Inc | 2024-07-03