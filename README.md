# Bio

func main() {
    heber := CyberPro{
        Alias:        "wr41th",
        Status:       "active",
        CurrentFocus: "Advanced Penetration Testing and Research",
        Expertise:    []string{"Web App Pentesting", "Backend Dev", "Golang/Python Dev"},
        Certifications: []string{"CompTIA Security+", "eJPT", "Google Information Security"},
    }

    heber.Skillset.OffensiveSec = []string{"Penetration Testing", "Exploit Development", "Vulnerability Assessment"}
    heber.Skillset.DefensiveSec = []string{"Splunk, Suricata, Zeek, Elastic"}
    heber.Skillset.Languages = []string{"Python", "Golang", "JavaScript", "Bash"}
    heber.Skillset.Tools = []string{"BurpSuite", "NVIM", "Python", "Golang"}

    heber.Projects.WebVulnScanner = "Zoomer, Comprehensive Web Scanner"
    heber.Projects.PentestingTool = "PoisonServer, Advanced server fingerprinting and exfiltration tool"
    heber.Projects.MLIntrusionSystem = "Shield, Machine learning-driven intrusion prevention system"
    heber.Projects.SyFiNetwork = "Sy-Fi-Networks.com, Cybersecurity community website with full-stack development"

    heber.Community.Platforms = []string{"TryHackMe", "HackTheBox", "HackerOne", "BugCrowd"}
    heber.Community = map[string]string{
        "TryHackMe", "HackTheBox"
    }

    heber.Contact.Website = "sy-fi-networks.com (coming soon)"
    heber.Contact.Email = "hmoreira89@proton.me"
    heber.Contact.LinkedIn = "linkedin.com/in/heber-moreira-a2501119a"

    fmt.Printf("%+v\n", heber)
}
